# watsonlesson

Website to Signup: https://www.ibmwatsonconversation.com






Code to Copy and paste later

{
“output”:{
	“text”: “and where do you want to fly from”
},
“context”:{
	“destination”: “<?@Airport?>”
	}
}




{
“output”:{
	“text”: “So when do you want to fly to $destination from @Airport”
},
“context”:{
	“origin”: “<?@Airport?>”
	}
}



{
“output”:{
	“text”: “And when do you want to come back?”
},
“context”:{
	“outDate”: “<?input.text.substring(20,30)?>”
	}
}



{
“output”:{
	“text”: “Ok so let me see what I can find for you. It may take a few seconds. /Flight”
},
“context”:{
	“returnDate”: “<?input.text.substring(20,30)?>”
	}
}
