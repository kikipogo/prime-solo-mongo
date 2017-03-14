dl class="m-b-none">
          <dt>Assignment Git Repo</dt>
          <dd><a target="_blank" href="https://github.com/kdszafranski/prime-mongo-crud-lecture-notes/">https://github.com/kdszafranski/prime-mongo-crud-lecture-notes/</a></dd>
      <dt>Description</dt>
      <dd><p>In this challenge, we’re going to practice basic Mongo syntax. This should help better solidify some concepts that were covered during lecture.</p>

<h1>Assumptions</h1>

<ul>
<li>You are using the mongo shell or Robomongo</li>
<li>You installed mongo via homebrew</li>
<li>mongod is currently running on your computer</li>
</ul>

<h1>Setup</h1>

<p>Follow the instructions below before continuing with this challenge.</p>

<h2>Create your database</h2>

<p>We are creating a database to hold a collection with at least 3 documents.</p>

<ol>
<li>Open mongo shell</li>
<li>Type <code>use phi</code> to create your database (or use an existing database)</li>
</ol>

<h2>GitHub repo</h2>

<ol>
<li>Create a GitHub repo named “prime-solo-mongo”. </li>
<li>Create a file called “mongo.txt”. You will store your responses to the exercise questions here. </li>
</ol>

<h1>Exercise</h1>

<p>For each of the following questions</p>

<ul>
<li>Write a comment that specifies which question you are answering. Use JavaScript comment syntax.</li>
<li>Write the Mongo query that answers the question, below that comment.</li>
</ul>

<h2>Example question and answer</h2>

<pre><code>// 0. Create a collection named joe
db.createCollection(&#39;joe&#39;)
</code></pre>

<h1>Tasks</h1>

<ol>
<li>Create a collection named orders.</li>
<li>Insert at least 3 documents that represent an order. IMPORTANT: See section below for fields.</li>
<li>Find a single order document, any order document.</li>
<li>Find all orders and make them look pretty.</li>
<li>Find all orders with an orderDate that is prior to 1/1/2016.</li>
<li>Find all orders with an orderDate that is after 1/1/2016.</li>
<li>Find orders with lineItems that have a quantity that is less than 50, but greater than 5. HINT: Look at <a href="https://docs.mongodb.com/v3.0/reference/operator/query/and/">$and</a> and  <a href="https://docs.mongodb.com/manual/core/document/#dot-notation">dot notation</a>.</li>
<li>Update one of your line items to 42.99. HINT: Look at <a href="https://docs.mongodb.com/manual/core/document/#dot-notation">dot notation</a></li>
<li>Remove one of your orders.</li>
</ol>

<h2>order fields</h2>

<ul>
<li>orderDate -- see <a href="https://docs.mongodb.org/manual/reference/method/Date/">https://docs.mongodb.org/manual/reference/method/Date/</a></li>
<li>orderTotal</li>
<li>lineItems -- an array of line item objects with fields

<ul>
<li>unitPrice</li>
<li>quantity</li>
<li>productName</li>
</ul></li>
</ul>
</dd>
    </dl
