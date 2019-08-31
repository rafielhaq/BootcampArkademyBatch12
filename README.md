# Batch 12 Arkademy Bootcamp

Jawaban tes online nomor 1 sampai 6 



## NOMOR 2

	function is_username_valid(username) {

	  var lowercaseRe = /[a-z]/g;
  
 	 var uppercaseRe = /[A-Z]/g;
  
	if(username.length == 5-9 
	&& username.match(lowercaseRe)
	&& username.match(uppercaseRe)
	.length == username.length) {
    	return true;
    }
    return false;
	}

	function is_password_valid(password) {
  
	var lowercaseRe = /[a-z]/g;
  
 	 var uppercaseRe = /[A-Z]/g;

 
 	 var numberRe = /[0-9]/g;

  
 	 var specialRe = /[_@#$%]/g;

 	 if(password.length == 8
     && lowercaseRe.test(password)
     && uppercaseRe.test(password)
     && numberRe.test(password)
     && specialRe.test(password)) {
     return true;
 	 }

 	 return false;
	}

## NOMOR 3




## NOMOR 4



## NOMOR 5



## NOMOR 6

