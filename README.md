# sample-swagger-for-nodejs

Sample of using <a href="http://swagger.io/">http://swagger.io/</a> for nodejs especially express framework.
<br>

<h3>Preview</h3>

<h3>Using technology</h3>
- NodeJS and Expressjs API development
- Swagger and Swagger UI for documentation

<br/>
<h3>Installation</h3>
- Install depedency <a href="https://github.com/swagger-api/swagger-node">https://github.com/swagger-api/swagger-node</a>
<pre>
npm install -g swagger
</pre>
- Install all depedency
<pre>
npm install
</pre>
- Run mongodb
<pre>
mongod
</pre>
- Run the server
<pre>
swagger project start
</pre>
- Open swagger editor
<pre>
swagger project edit
</pre>
- Open API documentation in browser
<pre>
<a href="http://localhost:10010/docs/#/default">http://localhost:10010/docs/#/default</a>
</pre>

<br/>
<h3>Folder Structure</h3>
- all code in <code>api</code> folder
- <code>api/connection/connection.js</code> is mongodb connection
- <code>app.js</code> is main server js
- folder <code>api/controllers</code> is all api routing
- folder <code>api/models</code> is schema model for mongodb ORM
- folder <code>api/swagger</code> is configuration for swagger UI

</br>
Hope will usefull for you all.</br>

Question ? please email : mazipanneh@gmail.com
