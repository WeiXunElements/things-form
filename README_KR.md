# things-form

#### 메타 데이터 FormFields 및 Buttons를 받아서 그 정보로 폼과 버튼을 구성한다. 그리고, 해당 폼에 대한 폼 데이터(Resource)를 받아서 화면에 바인딩한다. 이 후, 이벤트만 발생시키고 things-form을 사용한 곳에서 이벤트를 받아 버튼별 액션을 처리한다.

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

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install


## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polymer-cli

그리고, 아래의 방법을 통해 실행할 수 있다.

    polymer serve

element를 실행한 경우, `things-form`이 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-form/`을 통해 이를 미리 확인할 수 있다. 


## Example 1. Things Form
`<things-form>` Things Form
