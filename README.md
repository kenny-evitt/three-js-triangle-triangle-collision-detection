# three-js-triangle-triangle-collision-detection

This is an implementation of triangle-triangle collision detection in [three.js](https://threejs.org). It uses version 'r102' of three.js.

Open the file *two-triangles.html* in a web browser. You should see two triangles. (One, or maybe even both, might not be visible if the current camera position and orientation is such that a triangle is perfectly edge-on.)

At the top-left of the page, there should be text like "Do triangles intersect? Yes" (if the two triangles intersect).

Click anywhere with your left mouse button and drag the pointer around the page to rotate the camera around the triangles. Right-click and drag to pan the camera. Use your mouse scroll wheel to zoom in and out.

Click the "Randomize triangles" button to randomize the two triangles. The "Do triangles intersect?" text should update as appropriate. If the text indicates that the triangles intersect and they don't, or don't appear to, create an issue with the "Test case data" logged to the browser console; that data can be added to the `testCases` data in the code and serve as test case to be verified when the code is fixed.

Click the "Run tests" button to run tests for the fixed test cases (in the `testCases` variable in the JavaScript code in the *two-triangles.html* file). If any test cases fail, their data will be shown on the page.
