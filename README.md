# Digital-Design-II

## Digital Design Final Project Plan

Goals
1. ~Set up a GitHub account~ [done]
1. ~Create a project plan page with goals~ [done]
1. ~Instal GitHub Desktop~ [done]
1. ~Instal Atom~ [done]
1. ~Install atom packages~ [done]
    1. ~auto-update-packages~ [done]
    1. ~auto-close-html-plus~ [done]
    1. ~autocomplete-paths~ [done]
    1. ~highlight-selected~ [done]
    1. ~teletype~ [done]
    1. ~todo-show~ [done]
    1. ~atom-beautify~ [done]
1. ~Set up web project folders~ [done]
1. ~Create a simple game loop~ [done]
1. ~Create a page to handle gamepad events~ [done]
    1. ~Left, Right, Button 1, Button 2, ...~ [done]
1. ~Create a page to play video~ [done]
1. ~Add buttons to control the video~ [done]
    1. ~Play, Stop, Rewind, Fast Forward~ [done]
1. ~Add ability to control the video with gamepad~ [done]
    1. ~Play, Stop, Rewind, Fast Forward~ [done]

Publish project to GitHub and deploy to web server for each goal.

## Notes
* Basic html template https://www.sitepoint.com/a-basic-html5-template/
* Game loop basics http://gameprogrammingpatterns.com/game-loop.html
```
while (true)
{
  processInput();
  update();
  render();
}
```
* The Gamepad API https://developer.mozilla.org/en-US/docs/Web/API/Gamepad_API/Using_the_Gamepad_API
* The Media API https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs
* Start a simple web server with python
`python -m SimpleHTTPServer 8080`
