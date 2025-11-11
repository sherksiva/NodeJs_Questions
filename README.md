# NodeJs_Questions
Node JS interview Questions
#### *📘 HTTP Status Codes – Quick Cheat Sheet* 🌐

✅ *Success:*  
• *200 OK* – Request completed successfully  
• *201 Created* – New resource has been created  
• *204 No Content* – Successful, but nothing to return  

🔁 *Redirects:*  
• *301 Moved Permanently* – Resource moved to new URL  
• *302 Found* – Temporary redirect  
• *304 Not Modified* – Use cached response  

⚠️ *Client Errors:*  
• *400 Bad Request* – Invalid input  
• *401 Unauthorized* – Missing/invalid authentication  
• *403 Forbidden* – Authenticated but not allowed  
• *404 Not Found* – Resource doesn’t exist  
• *408 Request Timeout* – Client took too long  
• *409 Conflict* – Version/state conflict  

🔥 *Server Errors:*  
• *500 Internal Server Error* – Server crashed  
• *502 Bad Gateway* – Upstream server failed  
• *503 Service Unavailable* – Overloaded / maintenance  
• *504 Gateway Timeout* – Upstream took too long  

🎯 *Pro Tips:*  
– Use accurate status codes, not just 200/500  
– Include structured error responses  
– Never expose stack traces in production  
– Pair *304* with *ETag* for better caching  

💬 *Tap ❤️ for more!*
