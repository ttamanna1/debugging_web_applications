# Use Postman to Explore the JSON Placeholder Web API

> Learning Objective: Explain how HTTP requests and responses work at a high level

The routes of a web application are sometimes, collectively, called a Web API. They allow the web application to receive requests over the internet. Some APIs are _public_ and will accept requests from _anyone_. A good example of that is the JSON Placeholder Web API, which you already used in unit one.

Here, you're going to use Postman to send some requests to the JSON Placeholder Web API.

Work through these in order.

1. Use Postman to send a `GET` request to `https://jsonplaceholder.typicode.com/posts`. This will show you a list of all the existing `posts`.
2. Update your `GET` request to use a query parameter so that it returns only the posts that belong to the user with a `userId` of `1`.
3. Update your `GET` request to return only the post with an `id` of `1`. This will require a bit of research but there are two hints below, if you need them.
4. Do steps 1 to 3 for `https://jsonplaceholder.typicode.com/todos`
5. Do steps 1 to 3 for `https://jsonplaceholder.typicode.com/albums`
6. Compare and contrast the structure of these requests - what patterns do you see?

<br>
<details>
  <summary>
    A nudge in the right direction, for step 3
  </summary>
  <p>
    The JSON placeholder Web API routes all adhere to the RESTful routing convention.
  </p>
</details>
<br>
<details>
  <summary>
    Some more help with step 3, if you want it
  </summary>
  <p>
    <h3>The 7 RESTful routes for a photos app</h3>
    <table>
      <thead>
        <tr>
          <th><strong>Route</strong></th>
          <th><strong>HTTP Verb</strong></th>
          <th><strong>Purpose</strong></th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>/photos/</td>
          <td>GET</td>
          <td>listing all photos</td>
        </tr>
        <tr>
          <td>/photos/new</td>
          <td>GET</td>
          <td>getting the new photo form</td>
        </tr>
        <tr>
          <td>/photos</td>
          <td>POST</td>
          <td>submitting the new photo form</td>
        </tr>
        <tr>
          <td>/photos/:id</td>
          <td>GET</td>
          <td>showing one specific photo</td>
        </tr>
        <tr>
          <td>/photos/:id/edit</td>
          <td>GET</td>
          <td>getting the edit photo form</td>
        </tr>
        <tr>
          <td>/photos/:id</td>
          <td>PATCH/PUT</td>
          <td>submitting the edit photo form</td>
        </tr>
        <tr>
          <td>/photos/:id</td>
          <td>DELETE</td>
          <td>deleting a specific photo</td>
        </tr>
      </tbody>
    </table>
  </p>
</details>

<!-- BEGIN GENERATED SECTION DO NOT EDIT -->

---

**How was this resource?**  
[😫](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fweb-applications-in-python&prefill_File=paired_challenges%2Fuse_postman.md&prefill_Sentiment=😫) [😕](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fweb-applications-in-python&prefill_File=paired_challenges%2Fuse_postman.md&prefill_Sentiment=😕) [😐](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fweb-applications-in-python&prefill_File=paired_challenges%2Fuse_postman.md&prefill_Sentiment=😐) [🙂](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fweb-applications-in-python&prefill_File=paired_challenges%2Fuse_postman.md&prefill_Sentiment=🙂) [😀](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fweb-applications-in-python&prefill_File=paired_challenges%2Fuse_postman.md&prefill_Sentiment=😀)  
Click an emoji to tell us.

<!-- END GENERATED SECTION DO NOT EDIT -->
