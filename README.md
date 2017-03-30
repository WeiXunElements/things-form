# things-form

#### 메타 데이터 FormFields 및 Buttons를 받아서 그 정보로 폼과 버튼을 구성한다. 그 이후 해당 폼에 대한 폼 데이터(Resource)를 받아서 화면에 바인딩한다. 이 후 버튼별 액션은 이벤트만 던지고 things-form을 사용한 곳에서 이벤트를 받아 액션을 처리한다.

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

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

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


## Example 1. Things Form
`<things-form>` Things Form
