list all not in table, Here's a table listing the tags, properties, and attributes used in the HTML code you provided:

| Tag          | Property/Attribute        | Value                                                     |
|--------------|---------------------------|-----------------------------------------------------------|
| `<!DOCTYPE>` |                           |                                                           |
| `<html>`     | `lang`                    | `en`                                                      |
| `<head>`     |                           |                                                           |
| `<meta>`     | `charset`                 | `UTF-8`                                                   |
| `<meta>`     | `name`                    | `viewport`                                                |
|              | `content`                 | `width=device-width, initial-scale=1.0`                   |
| `<title>`    |                           | `About Anjana Neupane`                                    |
| `<style>`    |                           |                                                           |
|              |                           | CSS styles (commented out)                                |
| `</style>`   |                           |                                                           |
| `</head>`    |                           |                                                           |
| `<body>`     |                           |                                                           |
| `<h1>`       |                           |                                                           |
| `<strong>`   |                           |                                                           |
| `<p>`        | `<em>`                    |                                                           |
| `<b>`        |                           |                                                           |
| `<img>`      | `src`                     | `https://via.placeholder.com/150`                         |
|              | `alt`                     | `Anjana Neupane`                                          |
| `<a>`        | `href`                    | `https://www.wikipedia.org`                              |
|              | `target`                  | `_blank`                                                  |
|              | `rel`                     | `noopener noreferrer`                                    |
| `<hr>`       |                           |                                                           |
| `<strong>`   |                           |                                                           |
| `<ol>`       |                           |                                                           |
| `<ul>`       |                           |                                                           |
| `<li>`       |                           |                                                           |
| `<pre>`      |                           |                                                           |
| `<table>`    |                           |                                                           |
| `<tr>`       |                           |                                                           |
| `<th>`       |                           |                                                           |
| `<td>`       |                           |                                                           |
| `<form>`     |                           |                                                           |
| `<label>`    | `for`                     | `name`, `email`, `message`, `subscription`, `genre`       |
| `<input>`    | `type`                    | `text`, `email`, `checkbox`, `radio`, `submit`           |
|              | `id`                      | `name`, `email`, `message`, `subscription`, `male`, `female`, `other` |
|              | `name`                    | `name`, `email`, `message`, `subscription`, `gender`, `genre` |
|              |                           |                                                           |
| `<textarea>` | `id`                      | `message`                                                 |
|              | `name`                    | `message`                                                 |
| `<select>`   | `id`                      | `genre`                                                   |
|              | `name`                    | `genre`                                                   |
| `<option>`   | `value`                   | `technology`, `fiction`, `nonfiction`, `fantasy`         |
| `<button>`   | `type`                    | `submit`                                                  |

Not in the table:
- `<em>`: No attributes
- `<b>`: No attributes
- `<pre>`: No attributes
- `<form>`: No attributes
- `<label>`:
  - `for`: `name`, `email`, `message`, `subscription`, `genre`
- `<textarea>`:
  - `id`: `message`
  - `name`: `message`
- `<select>`:
  - `id`: `genre`
  - `name`: `genre`
- `<option>`:
  - `value`: `technology`, `fiction`, `nonfiction`, `fantasy`
- `<button>`:
  - `type`: `submit`

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Anjana Neupane</title>
    <style>
        /*
        body { font-family: Arial, sans-serif; background-color: #f4f4f9; color: #333; }
        h1, h2 { color: #333; }
        p, ol, ul, table, form { font-size: 16px; margin-top: 20px; }
        img { width: 150px; border-radius: 75px; }
        table { border-collapse: collapse; width: 100%; }
        td, th { border: 1px solid #ddd; padding: 8px; text-align: left; }
        label, button { display: block; margin-top: 10px; }
        input, textarea, select { width: 100%; padding: 8px; margin-top: 5px; }
        button { padding: 10px 20px; background-color: #5c67f2; color: white; border: none; border-radius: 4px; cursor: pointer; }
        button:hover { background-color: #5058cc; }
        */
    </style>
</head>
<body>
    <h1>Hello,</h1>
    <h3>I'm Anjana Neupane!</h3>
    <p><em>Welcome to my personal webpage. </em></p>
       <b> I'm a full-stack developer with a passion for building meaningful web applications.</b>
       <br>
    <img src="https://cdn.pixabay.com/photo/2015/10/09/00/55/lotus-978659_1280.jpg" alt="Anjana Neupane" height="100px">
    <p>Check out <a href="https://www.wikipedia.org" target="_blank" rel="noopener noreferrer">Wikipedia</a> for more interesting reads.</p>

    <hr>
    <strong>Here are a few of my interests:</strong>
    <ol>
        <li>Coding and development</li>
        <li>Hiking and outdoor activities</li>
        <li>Reading tech articles</li>
    </ol>
    <hr>
    <strong>Some books I recommend:</strong>
    <ul>
        <li>Clean Code by Robert C. Martin</li>
        <li>The Pragmatic Programmer by Andrew Hunt</li>
        <li>Don't Make Me Think by Steve Krug</li>
    </ul>
    <pre>
        Email: anjana.neupane@example.com
        Phone: +9876543210
    </pre>
    <hr>
    <table border="1">
        <tr>
            <th>SN</th>
            <th>Contact Detail</th>
            <th>Information</th>
            <th>Address</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Email</td>
            <td>anjana.neupane@example.com</td>
            <td rowspan="2">Gautam Chowk</td>
        </tr>
        
        <tr>
            <td>2</td>
            <td>Phone</td>
            <td>+9876543210</td>
        </tr>
    </table>
    <hr>
    <h2>Contact Me</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        <br>
        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea>
        <br>
        <label for="updates">Sign up for updates:</label>
        <input type="checkbox" id="updates" name="updates">
        <label for="contact-preference">Preferred method of contact:</label>
        <br>
        <input type="radio" id="email-contact" name="contact-method" value="email" checked>Email
        <br>
        <input type="radio" id="phone-contact" name="contact-method" value="phone">Phone
        <br>
        <label for="genre">Favorite Genre:</label>
        <select id="genre" name="genre">
            <br>
            <option value="technology">Technology</option>
            <option value="fiction">Fiction</option>
            <option value="nonfiction">Nonfiction</option>
            <option value="fantasy">Fantasy</option>
        </select>
        <br>
        <button type="submit">Send Message</button>
        <br>
    </form>
</body>
</html>

```
