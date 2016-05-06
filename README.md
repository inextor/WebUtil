# axhrw
Another XMLHttpRequest Wrapper

```js
	promise = axhrw
	({
		method				: 'POST'		//,'POST',...
		,success			: function( response )
    ,data         : 
    {
      
    }
	});
	```
	
	Other Options
	
	 timeout				: 3000 	
		,method				: 'GET'		
		,async				: true			
		,url				: 'The url'		//Required
		,user				: ''
		,password			: ''
		,withCredentials	: false
		,requestHeaders		: { Content-type : 'text/html' }
		,data				: xxxx
		,responseType		: ''//arrayBuffer,blob,document,json,text
		,overrideMimeType	: 'text/plain; charset=utf-8'
		,success			: function( response, status, responseHeaders )
		,uploadFinish: function()
		,uploadProgress	: function( evt )
		,progress			: function( evt )
		,error			: function( xhr, statusText, e )
		,abort			: function()
	
