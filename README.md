# reactjs-assigment01
step 1:
run command
npm install 

<h2>💿 Installation</h2>

<p>Run these commands in the terminal:</p>

<ol>
  <li>
    <code>$ git clone git@github.com:TowhidKashem/snapchat-clone.git</code>
  </li>
  <li><code>$ cd snapchat-clone</code></li>
  <li>
    <code>$ npm install</code>
    <ul>
      <li>
        This will:
        <ul>
          <li>Install the dependencies in package.json</li>
          <li>
            Checkout
            <a href="https://github.com/jeeliz/jeelizFaceFilter">jeelizFaceFilter</a>
            package (used for the filters) and set it to the last version this
            project was tested and confirmed to work with
          </li>
          <li>
            Run <code>gulp</code> to concatenate, minify and transpile the files
            located in <code>public/filters/source/*.js</code> into a single
            file called <code>filters.min.js</code>
          </li>
        </ul>
      </li>
    </ul>
  </li>
  <li>
    This part is optional but strongly recommended, without it you won't be able
    to view any of the snap map features:
    <ul>
      <li>
        Make a Mapbox account and
        <a
          href="https://docs.mapbox.com/help/glossary/access-token/"
          target="_blank"
          >get a free API key</a
        >
      </li>
      <li>
        In the <code>.env</code> file enter your new API key, for example:
        <ul>
          <li>
            Before:
            <code>REACT_APP_MAP_BOX_API_KEY=REPLACE_WITH_API_KEY</code>
          </li>
          <li>After: <code>REACT_APP_MAP_BOX_API_KEY=xy.abc123</code></li>
        </ul>
      </li>
    </ul>
  </li>
  <li>
    <code>$ npm start</code>
    <ul>
      <li>
        The app should open automatically in your browser usually at
        <code>https://localhost:3000/</code>
        <ul>
          <li>
            In Chrome you will receive a "Your connection is not private"
            warning
            <ul>
              <li>
                Click "Advanced" &gt; "Proceed to localhost (unsafe)"
                <ul>
                  <li>
                    You'll get this warning because the app uses a self signed
                    <code>https</code> certificate. The
                    <code>getUserMedia</code> API used by the camera requires
                    the <code>https</code> protocol so we run the dev server in
                    https mode.
                  </li>
                </ul>
              </li>
            </ul>
          </li>
          <li>
            After this you will be prompted to give access to your webcam, click
            "Allow"
          </li>
        </ul>
      </li>
    </ul>
    <br />
    <table>
      <tbody>
        <tr>
          <th align="center">
            Step 1
          </th>
          <th align="center">
            Step 2
          </th>
          <th align="center">
            Step 3
          </th>
        </tr>
        <tr>
          <td align="center" valign="middle">
            <img src="public/readme/step1.png" />
          </td>
          <td align="center" valign="middle">
            <img src="public/readme/step2.png" />
          </td>
          <td align="center" valign="middle">
            <img src="public/readme/camera.png" />
          </td>
        </tr>
      </tbody>
    </table>
  </li>
  <li>You're all set! 🎉</li>
</ol>
