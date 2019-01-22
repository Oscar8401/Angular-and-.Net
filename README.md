# The repository has been moved to bitbucket.
# For further information please contact me <cite>taleb_n1@hotmail.com</cite>

# Serverless-App-on-Azure:
&nbsp;&nbsp;&nbsp;Serverless Angular Application on Azure.

# Required:
Node.js v6.5.0 or later.
<br>Serverless cli v1.9.0 or later.
<br>Azure plugin that allows working with Azure function.
<br>Aure account.

# Installation:
<ul>1. Create a new service:
  <li>$serverless create--template azure-node.js--path my-service--name my-unique-name</li>
  <li>$cd my-service</li>
  <li>$npm install</li>
</ul>
<ul>2. Deploy and test:
  <li>1. Deploy the service: serverless deploy</li>
  <li>2. Deploy the function: serverless deploy function -f hello</li>
  <li>3. Invoke the function: serverless invoke -f hello</li>
  <li>4. Fetch the function logs: serverless logs -f hello -t</li>
</ul>
<ul>3. Clean up:
<li>serverless remove</li>
</ul>

# Information
  &nbsp;&nbsp;&nbsp;Authors:
  <br>
      &nbsp;&nbsp;&nbsp;<a href="https://github.com/Taleb01">Taleb O. M.</a>
      
# References:
  &nbsp;&nbsp;&nbsp;More Information:
  <br>
     &nbsp;&nbsp;&nbsp;<a href="https://angular.io/">Angular framework</a>
     <br>
     &nbsp;&nbsp;&nbsp;<a href="https://docs.microsoft.com/en-us/iis/extensions/url-rewrite-module/creating-rewrite-rules-for-the-url-rewrite-module">URL rewrite Doc</a>
     <br>
     &nbsp;&nbsp;&nbsp;<a href="https://docs.microsoft.com/en-us/azure/azure-functions/functions-how-to-use-azure-function-app-settings">Azure Functions Docs</a>

     
# License:
&nbsp;&nbsp;&nbsp;MIT License Copyright 2018
&nbsp;&nbsp;&nbsp;<p>Permission is hereby granted, <b>free of charge</b>, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
  <br><br>
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.</p>
