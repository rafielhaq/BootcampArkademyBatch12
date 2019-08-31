# Batch 12 Arkademy Bootcamp

Jawaban tes online nomor 1 sampai 6 

## NOMOR 1

	function getProfile() {
 	 return {
  
    "name":"Muhammad Rofiul haq",
    "age":21,
    "address":"Jl.Padat Karya I ,Balikpapan",
    "hobbies": ["Football", "table tennis"] ,
    "is_married": false,
    "list_school": [{
      "name": "MA ALKHAIRAT PUSAT PALU",
      "year_in":2012,
      "year_out":2015,
      "major":"sience",
    }], 
    "skills": [{
      "name": "English",
      "level": "advanced"
    },{
      "name": "communication",
      "level":"advanced"
    }],
    "interest_in_coding": true,
  }

  // JSON yaitu format untuk mentransmisikan (mengirim dan menerima) data web API (server) ke client atau sebaliknya.

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

