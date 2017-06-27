# things-form

#### The component receives FormFields and Buttons of the meta data and constructs the form and button with that information. Then, it receives the form data (Resource) for the corresponding form and binds it to the screen. After that, it only fires an event and receives the event where it used things-form to proceed the action of each button.

Example:

```html
    <form is="iron-form"
          id="form"
          action=[[action]]
          headers="[[headers]]"
          content-type="[[contentType]]"
          method="[[method]]"
          with-credentials="[[withCredentials]]"
          last-response="{{lastResponse}}">
        <div id="fields" class="layout vertical flex"></div>
    </form>
```


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-form/`, where `things-form` is the name of the directory containing it.
