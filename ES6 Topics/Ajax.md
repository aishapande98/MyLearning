What is AJAX
===================================

 * AJAX is Asynchronous Javascript and XML.
 * AJAX is not a programming language.
 * It uses combination of:
     * A browser built-in XMLhttpRequest object(To request a data from the server).
     * Javascript and HTML DOM.
  * AJAX updates web pages asynchronously by exchanging data with server behind the scenes. It means AJAX updates web page withour re-loading the page.
  
  
## How AJAX works:
    
   * An event occurs in a web page (i.e button-clicked,page is loaded).
   * The XMLhttpRequest object is created by Javascript.
   * XMLhttpRequest sends request to a web server.
   * Server process that request.
   * The server sends response back to a web page.
   * The response is read by a Javascript.
   * Proper action is taken by Javascript.
    
 ### XMLhttpRequest Object:
 
   * All modern browsers like (chrome,mozilla,IE 7,Edge,Safari) have a built in XMLhttpRequest object.
   * Below is the syntax to create XMLhttpRequest object
       * variable =new XMLhttpRequest();
       
  ### ActiveXObject:
   
   * Old versions of IE i.e IE 5,6 uses ActiveXObject to send request to a server instead of XMLhttpRequest Object.
   * To hadle this browsers check if it supports XMLhtppRequest object else use ActiveXObject.
  
     
### XMLhttpRequest object properties
  
   * onreadystatechange: Defines a function that to be called on state change.
   * readyState: It holds the status of XMLhttpRequest.
        * 0: Request not initialized.
        * 1: Server connection established.
        * 2: Request recevied.
        * 3: Processing request.
        * 4: Response is ready.
        
 ### Send a request to a server
 
   *  To send a request to a server use a Open() and send() method:
        * Open(method,URL,async): It specifies the type of request
             * method: Get or Post
             * URL: file location
             * async: Server requests to be send asynchronously.
    

  
  
  
  
