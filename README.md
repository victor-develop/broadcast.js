# broadcast.js
minimal browser-based central event bus

# usage
 - include this into script tag
 
 ```javascript
 //fire an event
   simpleBroadcast('something-happen',{
     data:"sample text I want to deliver"
   });
 //listen on an event
   onSimpleBroadcast('something-happen',function(event)){
     console.log(event.detail.data); // "sample text I want to deliver"
   }
 ```
 
