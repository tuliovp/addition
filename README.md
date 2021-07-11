<h1>Description</h1>
                  <hr>
                  <p>
                    To create apps with interactive UIs that will render data updates, React can be really helpful.
                    <br><br>
                    First I load and unpack the version of <code>react</code> and <code>react-dom</code>, keeping the <code>crossorigin</code> attribute set.
                    Then, I add an attribute to script tag for babel to translate this code to AJAX and create a Class component called <code>App</code>.
                    Components let you split the UI into independent, reusable pieces, and think about each piece in isolation. They accept arbitrary inputs 
                    (called “props”) and return React elements describing what should appear on the screen.
                    <br><br>Components serve the same purpose as JavaScript functions, but work in isolation and return HTML via a render() function. 
                    In this case, it will render simple random addition problems and the "You won!" message <code>if(this.state.score === 5)</code>.
                    <br><br>I have created different events which will be updated when the Enter key is <code>inputKeyPress</code> - extracting the answer and
                    checking if it is correct. If so, <code>score: state.score + 1</code>. If not, <code>score: state.score - 1</code>.
                  </p>
                  <br>
                  <h1>Read more</h1>
                  <hr>
                  <p>This web application is available in the following APP button. 
                    The source code of the project is on Github.</p>
                    <br>
                    <div class="row">
                      <div class="column">
                        <a class="btn btn-secondary btn text-uppercase" href="https://github.com/tuliovp/addition/blob/main/index.html">Github</a>
                      </div>
                      <div class="column">
                        <a class="btn btn-secondary btn text-uppercase" href="https://tuliovp.github.io/addition/">App</a>
                      </div>
                    </div>
                