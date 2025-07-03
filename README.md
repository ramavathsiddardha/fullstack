<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>siddu</title>
    
</head>
<body>
  <h1>Essential HTML Tags Reference</h1>
  <p>A comphensive showcase of all important HTML tags</p>
  <h2>Navigation Menu</h2>
  <ul>
    <li><a href="#text">Text Formation</a></li>
    <li><a href="#lists">Lists</a></li>
    <li><a href="#media">Media</a></li>
    <li><a href="#Tables">Tables</a></li>
    <li><a href="#forms">Forms</a></li>
    <li><a href="#sematic HTML">Semantic HTML</a></li>
  </ul>
  <h2>Text Formatting Tags</h2>
  <p>Headings (h1-h6)</p>
  <h1>Heading level 1</h1>
  <h2>Heading level 2</h2>
  <h3>Heading level 3</h3>
  <h4>Heading level 4</h4>
  <h5>Heading level 5</h5>
  <h6>Heading level 6</h6>
  <h3>Paragraphs and Formating</h3>
  <p>Lorem ipsum dolor <strong>sit amet consectetur</strong> adipisicing elit.<mark> Animi ullam</mark> quae alias molestiae, aperiam, sed doloremque repellendus odit iusto illum asperiores molestias modi natus nostrum recusandae? Suscipit quisquam tempore sed?</p>
  <p>E=mc<sup>2</sup>,H<sub>2</sub>O</p>
  <pre>preformated Text preseserves
         spaces  and 
              line breaks
  </pre>
  
  <h2>Lists Tags</h2>
  <h3>Unordered lists(ul)</h3>
  <ul>
    <li>First item</li>
    <li>second item</li>
    <li>Third item</li>
    <ul>
        <li>Fourth item</li>
        <li>Five item</li>
    </ul>
    </ul>
    <h3>Ordered Lists(ol)</h3>
    <ol>
        <li>First step</li>
        <li>Second step</li>
        <li>Third step</li>
        <ol type="a">
            <li>Sub-step a</li>
            <li>Sub-step b </li>
        </ol>
    </ol>
    <h3>Description List</h3>
    HTML
    <section>
        <article>
            <h3>Audio (audio)</h3>
            <audio controls>
                <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
                youur browser does not support the audio element.
            </audio>
        </article>

       <article>
    <h3>Video (salaar trailer)</h3>
    <iframe width="560" height="315"
      src="https://www.youtube.com/embed/9Im1q4gvk1M"
      title="SALÂAR — Official Trailer"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen>
    </iframe>
    <p>Official trailer for Salaar starring Prabhas</p>
  </article>
    </section>
    <main>
        <section id="tables">
            <article>
                <h3>Comlex Table</h3>
                <table border="1">
                    <tr>
                        <th rowspan="2">Name</th>
                        <th colspan="2">Contact</th>
                    </tr>
                    <tr>
                        <th>Email</th>
                        <th>Phone</th>
                    </tr>
                    <tr>
                        <td>John Doe</td>
                        <td>John@exapmle.com</td>
                        <td>123-4567</td>
                    </tr>
                </table>
            </article>
        </section>
    </main>
    <h2>Form Tags</h2>
    <h3>Basic Form</h3>
    <form action="/submit" method="post">
        <fieldset>
            <legend>Personal Information</legend>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name"><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required><br><br>
            <label for="age">Age:</label>
            <input type="age" id="age" name="age" ><br><br>
            <label for="birthday">Birthday:</label>
            <input type="date" id="dop" name="dop" required><br><br>
        </fieldset>
        <fieldset>
            <legend>Preferences</legend>
            <label for="bio">Bio</label>
            <input type="text-area" name="bio" id="bio" rows="70" cols="50"><br>
            <label for="Gender">Gender:</label>
            Male<input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> 
            Female<label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> </label><br><br>
            <label for="car">Car:</label>
            <select id="car" name="car">
                <option value="volvo">Volvo</option>
                <option value="saaab">Saab</option>
                <option value="mercedes">Mercedes</option>
            </select><br><br>
            <label for="country">country</label>
            <select id=""country" name="country">
              <option value="">Select a country</option>
              <optgroup label="Asia"></optgroup>
              <option value="china">China</option>
              <option value="india">INDIA</option>
              </optgroup>
              <optgroup label="West">
               <option value="us">USA</option>
               <option value="fr">France</option>
              </optgroup>
              
           </select><br><br>
           <label for="volume">Volume:</label>
           <input type="range" id="range" min="30" max="100">
   
        </fieldset>
        <button >Submit Form</button>
        <button>Reset</button>
    </form>
    <h2>Semantic HTML Tags</h2>

    <h3>Document Structure</h3>
    <details>
        <summary>Details & Summary</summary>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia dolore error molestiae provident quaerat laboriosam accusamus, similique amet voluptatibus facere excepturi animi sapiente veritatis repellendus officia et perspiciatis quo? Assumenda.</p>
    </details>
    <img src="data:image/jpeg;base64,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" alt="HIT THIRD CASE"> 
     <body>
</html>
