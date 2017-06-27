# things-dialog-manager
## 이는 모든 Things Client 내 프레임웤 부분의 Dialog를 Open 및 Close해 주는 컴포넌트이다.

Example)
```html
<things-dialog-manager locale=[[globals.locale]]>
</things-dialog-manager>
```
### 아래와 같은 Event들을 받고 Dialog를 오픈한다.
```
things-open-popup-view,
things-open-custom-size-dialog,
things-open-menu-detail-view,
things-detail-view-created,
things-date-picker-toggle,
things-image-selector-toggle,
things-file-selector-toggle,
things-import-dialog-toggle,
things-image-dialog-toggle,
things-dialog-close,
things-all-dialog-close,
things-date-picker-close,
things-image-selector-close,
things-file-selector-close,
things-import-dialog-close,
things-image-dialog-close
```

## Dependencies

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install


## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polyserve

그리고, 아래의 방법을 통해 실행할 수 있다.

    polyserve

element를 실행한 경우, `things-dialog-manager`가 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-dialog-manager/`를 통해 이를 미리 확인할 수 있다. 
