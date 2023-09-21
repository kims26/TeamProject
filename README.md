# 전기차 충전소 


<p align="center">
<img width="60%" src="https://github.com/kims26/TeamProject/assets/114653761/5d4614a5-fafc-4828-929b-04891f9eae9f">
</p>
<br><br>

# EV-CHarging 소개

**EV-CHarging**의 기획 의도는 지난 10년간

1.시장의 급속한 성장

2. 충전사업자 무분별하게 증가

이로 인해 다양한 문제 발생




<br><br>

# 팀원소개

<p align="center">
<img width="60%" src="https://github.com/kims26/TeamProject/assets/114653761/b85ae0f7-23ec-4232-847f-450411d80129">

</p>

# 기술스택

<p align="center">
<img width="60%" src="https://github.com/kims26/TeamProject/assets/114653761/b06d0837-d90b-4b61-9550-10c4cf5cacf7">
</p>

# Data Flow

<p align="center">
<img width="60%" src="https://github.com/kims26/TeamProject/assets/114653761/f9f142aa-a516-4152-ab2d-fbe46b593586">
</p>

# ERD

<p align="center">
<img width="60%" src="https://github.com/kims26/TeamProject/assets/114653761/7fbff21f-6e00-456f-aa3e-c42e63bfec76">
</p>





# 서버 폴더구조

```

```
TeamFinalProject
├─ .DS_Store
├─ .gitignore
├─ .mvn
│  └─ wrapper
│     ├─ maven-wrapper.jar
│     └─ maven-wrapper.properties
├─ DB.sql
├─ bin
│  ├─ .gitignore
│  ├─ .mvn
│  │  └─ wrapper
│  │     ├─ maven-wrapper.jar
│  │     └─ maven-wrapper.properties
│  ├─ mvnw
│  ├─ mvnw.cmd
│  ├─ pom.xml
│  └─ src
│     ├─ main
│     │  ├─ java
│     │  │  └─ FinalProject
│     │  │     └─ demo_final
│     │  │        ├─ DemoFinalApplication.class
│     │  │        ├─ controller
│     │  │        │  └─ MainController.class
│     │  │        ├─ dao
│     │  │        ├─ main.js
│     │  │        └─ vo
│     │  ├─ resources
│     │  │  ├─ application.properties
│     │  │  ├─ mybatis
│     │  │  │  └─ mapper
│     │  │  ├─ static
│     │  │  │  └─ index.html
│     │  │  └─ templates
│     │  └─ webapp
│     │     ├─ WEB-INF
│     │     │  └─ views
│     │     │     └─ main
│     │     ├─ css
│     │     │  ├─ main.css
│     │     │  ├─ main_footer.css
│     │     │  ├─ main_header.css
│     │     │  ├─ main_header_responsive.css
│     │     │  └─ reset.css
│     │     ├─ images
│     │     │  └─ search.png
│     │     └─ main
│     │        └─ main.jsp
│     └─ test
│        └─ java
│           └─ FinalProject
│              └─ demo_final
│                 └─ DemoFinalApplicationTests.class
├─ min2
│  ├─ .DS_Store
│  ├─ .git
│  │  ├─ HEAD
│  │  ├─ config
│  │  ├─ description
│  │  ├─ hooks
│  │  │  ├─ applypatch-msg.sample
│  │  │  ├─ commit-msg.sample
│  │  │  ├─ fsmonitor-watchman.sample
│  │  │  ├─ post-update.sample
│  │  │  ├─ pre-applypatch.sample
│  │  │  ├─ pre-commit.sample
│  │  │  ├─ pre-merge-commit.sample
│  │  │  ├─ pre-push.sample
│  │  │  ├─ pre-rebase.sample
│  │  │  ├─ pre-receive.sample
│  │  │  ├─ prepare-commit-msg.sample
│  │  │  ├─ push-to-checkout.sample
│  │  │  ├─ sendemail-validate.sample
│  │  │  └─ update.sample
│  │  ├─ index
│  │  ├─ info
│  │  │  └─ exclude
│  │  ├─ logs
│  │  │  ├─ HEAD
│  │  │  └─ refs
│  │  │     ├─ heads
│  │  │     │  └─ main
│  │  │     └─ remotes
│  │  │        └─ origin
│  │  │           └─ HEAD
│  │  ├─ objects
│  │  │  ├─ info
│  │  │  └─ pack
│  │  │     ├─ pack-4c9c06c468f39654667d87e5c3ececb6b01863ee.idx
│  │  │     ├─ pack-4c9c06c468f39654667d87e5c3ececb6b01863ee.pack
│  │  │     └─ pack-4c9c06c468f39654667d87e5c3ececb6b01863ee.rev
│  │  ├─ packed-refs
│  │  └─ refs
│  │     ├─ heads
│  │     │  └─ main
│  │     ├─ remotes
│  │     │  └─ origin
│  │     │     └─ HEAD
│  │     └─ tags
│  └─ README.md
├─ mvnw
├─ mvnw.cmd
├─ pom.xml
└─ src
   ├─ .DS_Store
   ├─ main
   │  ├─ .DS_Store
   │  ├─ java
   │  │  ├─ .DS_Store
   │  │  ├─ demo_final
   │  │  │  ├─ .DS_Store
   │  │  │  ├─ DemoFinalApplication.java
   │  │  │  ├─ controller
   │  │  │  │  ├─ .DS_Store
   │  │  │  │  ├─ AdminController.java
   │  │  │  │  ├─ ApiOperation.java
   │  │  │  │  ├─ BoardController.java
   │  │  │  │  ├─ CartController.java
   │  │  │  │  ├─ ChargeController.java
   │  │  │  │  ├─ CommentBoardController.java
   │  │  │  │  ├─ FavoriteController.java
   │  │  │  │  ├─ KakaoPayController.java
   │  │  │  │  ├─ LoginController.java
   │  │  │  │  ├─ MailController.java
   │  │  │  │  ├─ MainController.java
   │  │  │  │  ├─ MemberController.java
   │  │  │  │  ├─ NaverLoginApi.java
   │  │  │  │  ├─ NaverLoginBO.java
   │  │  │  │  ├─ OwnerController.java
   │  │  │  │  ├─ PaymentController.java
   │  │  │  │  └─ ProductController.java
   │  │  │  ├─ dao
   │  │  │  │  ├─ AdminDao.java
   │  │  │  │  ├─ BoardDao.java
   │  │  │  │  ├─ CartDao.java
   │  │  │  │  ├─ CategoryDao.java
   │  │  │  │  ├─ CommentBoardDao.java
   │  │  │  │  ├─ DeliveryDao.java
   │  │  │  │  ├─ FavoriteDao.java
   │  │  │  │  ├─ MemberDao.java
   │  │  │  │  ├─ OwnerDao.java
   │  │  │  │  ├─ PaymentDao.java
   │  │  │  │  └─ ProductDao.java
   │  │  │  ├─ service
   │  │  │  │  ├─ KakaoPayService.java
   │  │  │  │  └─ Mailservice.java
   │  │  │  └─ vo
   │  │  │     ├─ AdminVo.java
   │  │  │     ├─ Amount.java
   │  │  │     ├─ BoardVo.java
   │  │  │     ├─ CartVo.java
   │  │  │     ├─ CategoryVo.java
   │  │  │     ├─ ChargeVo.java
   │  │  │     ├─ CommentBoardVo.java
   │  │  │     ├─ DeliveryVo.java
   │  │  │     ├─ FavoriteVo.java
   │  │  │     ├─ KakaoApproveResponse.java
   │  │  │     ├─ KakaoReadyResponse.java
   │  │  │     ├─ MailVo.java
   │  │  │     ├─ MemberVo.java
   │  │  │     ├─ OwnerVo.java
   │  │  │     ├─ PaymentParam.java
   │  │  │     ├─ PaymentVo.java
   │  │  │     └─ ProductVo.java
   │  │  └─ util
   │  │     ├─ ChargeSearchUtils.java
   │  │     ├─ MyConstant.java
   │  │     ├─ MyDistance.java
   │  │     └─ Paging.java
   │  ├─ resources
   │  │  ├─ .DS_Store
   │  │  ├─ application.properties
   │  │  ├─ mybatis
   │  │  │  ├─ .DS_Store
   │  │  │  └─ mapper
   │  │  │     ├─ admin.xml
   │  │  │     ├─ board.xml
   │  │  │     ├─ cart.xml
   │  │  │     ├─ category.xml
   │  │  │     ├─ commentboard.xml
   │  │  │     ├─ delivery.xml
   │  │  │     ├─ favorite.xml
   │  │  │     ├─ member.xml
   │  │  │     ├─ owner.xml
   │  │  │     ├─ payment.xml
   │  │  │     └─ product.xml
   │  │  ├─ static
   │  │  │  └─ index.html
   │  │  └─ templates
   │  └─ webapp
   │     ├─ .DS_Store
   │     ├─ WEB-INF
   │     │  ├─ .DS_Store
   │     │  └─ views
   │     │     ├─ category
   │     │     │  ├─ a_type_category.jsp
   │     │     │  ├─ b_type_category.jsp
   │     │     │  └─ c_type_category.jsp
   │     │     ├─ owner
   │     │     │  ├─ admin_footer.jsp
   │     │     │  ├─ owner_chart.jsp
   │     │     │  ├─ owner_insert_form.jsp
   │     │     │  ├─ owner_insert_msg.jsp
   │     │     │  ├─ owner_list.jsp
   │     │     │  ├─ owner_login_form.jsp
   │     │     │  ├─ owner_modify_form.jsp
   │     │     │  ├─ owner_order.jsp
   │     │     │  ├─ owner_pay.jsp
   │     │     │  ├─ owner_pay_list.jsp
   │     │     │  ├─ owner_pay_succ.jsp
   │     │     │  ├─ owner_product_list.jsp
   │     │     │  ├─ owner_sales_rate.jsp
   │     │     │  ├─ owner_sidebar.jsp
   │     │     │  ├─ owner_topbar.jsp
   │     │     │  └─ owner_wait.jsp
   │     │     ├─ product
   │     │     │  ├─ cart_list.jsp
   │     │     │  ├─ product_cart_payment_list.jsp
   │     │     │  ├─ product_insert_form.jsp
   │     │     │  ├─ product_list.jsp
   │     │     │  ├─ product_main_page.jsp
   │     │     │  ├─ product_modify_form.jsp
   │     │     │  ├─ product_page_form.jsp
   │     │     │  └─ product_test.jsp
   │     │     └─ search
   │     │        └─ search_main.jsp
   │     ├
   │     ├─ finaljs
   │     │  └─ finaljs
   │     │     ├─ accordions.js
   │     │     ├─ bootstrap.min.js
   │     │     ├─ custom.js
   │     │     ├─ datepicker.js
   │     │     ├─ imgfix.min.js
   │     │     ├─ isotope.js
   │     │     ├─ jquery-2.1.0.min.js
   │     │     ├─ jquery.counterup.min.js
   │     │     ├─ lightbox.js
   │     │     ├─ owl-carousel.js
   │     │     ├─ popper.js
   │     │     ├─ quantity.js
   │     │     ├─ scrollreveal.min.js
   │     │     ├─ slick.js
   │     │     └─ waypoints.min.js
   │     ├─
   │     ├─ js
   │     │  ├─ bootstrap.bundle.min.js
   │     │  ├─ custom.js
   │     │  ├─ final.js
   │     │  ├─ jquery-1.11.0.min.js
   │     │  ├─ jquery-migrate-1.2.1.min.js
   │     │  ├─ slick.min.js
   │     │  ├─ templatemo.js
   │     │  └─ templatemo.min.js
   │     ├
   │     ├─ resources
   │     │  
   │     │  ├─ js
   │     │  │  ├─ demo
   │     │  │  │  ├─ chart-area-demo.js
   │     │  │  │  ├─ chart-bar-demo.js
   │     │  │  │  ├─ chart-pie-demo.js
   │     │  │  │  └─ datatables-demo.js
   │     │  │  ├─ sb-admin-2.js
   │     │  │  └─ sb-admin-2.min.js
   │     │  ├─ package-lock.json
   │     │  ├─ package.json
   │     │  ├─ sample_data.json
   │     │  ├─ scss
   │     │  │  ├─ _buttons.scss
   │     │  │  ├─ _cards.scss
   │     │  │  ├─ _charts.scss
   │     │  │  ├─ _dropdowns.scss
   │     │  │  ├─ _error.scss
   │     │  │  ├─ _footer.scss
   │     │  │  ├─ _global.scss
   │     │  │  ├─ _login.scss
   │     │  │  ├─ _mixins.scss
   │     │  │  ├─ _navs.scss
   │     │  │  ├─ _utilities.scss
   │     │  │  ├─ _variables.scss
   │     │  │  ├─ navs
   │     │  │  │  ├─ _global.scss
   │     │  │  │  ├─ _sidebar.scss
   │     │  │  │  └─ _topbar.scss
   │     │  │  ├─ sb-admin-2.scss
   │     │  │  └─ utilities
   │     │  │     ├─ _animation.scss
   │     │  │     ├─ _background.scss
   │     │  │     ├─ _border.scss
   │     │  │     ├─ _display.scss
   │     │  │     ├─ _progress.scss
   │     │  │     ├─ _rotate.scss
   │     │  │     └─ _text.scss
   │     │  └─ vendor
   │     │     ├─ bootstrap
   │     │     │  ├─ js
   │     │     │  │  ├─ bootstrap.bundle.js
   │     │     │  │  ├─ bootstrap.bundle.js.map
   │     │     │  │  ├─ bootstrap.bundle.min.js
   │     │     │  │  ├─ bootstrap.bundle.min.js.map
   │     │     │  │  ├─ bootstrap.js
   │     │     │  │  ├─ bootstrap.js.map
   │     │     │  │  ├─ bootstrap.min.js
   │     │     │  │  └─ bootstrap.min.js.map
   │     │     │  └─ scss
   │     │     │     ├─ _alert.scss
   │     │     │     ├─ _badge.scss
   │     │     │     ├─ _breadcrumb.scss
   │     │     │     ├─ _button-group.scss
   │     │     │     ├─ _buttons.scss
   │     │     │     ├─ _card.scss
   │     │     │     ├─ _carousel.scss
   │     │     │     ├─ _close.scss
   │     │     │     ├─ _code.scss
   │     │     │     ├─ _custom-forms.scss
   │     │     │     ├─ _dropdown.scss
   │     │     │     ├─ _forms.scss
   │     │     │     ├─ _functions.scss
   │     │     │     ├─ _grid.scss
   │     │     │     ├─ _images.scss
   │     │     │     ├─ _input-group.scss
   │     │     │     ├─ _jumbotron.scss
   │     │     │     ├─ _list-group.scss
   │     │     │     ├─ _media.scss
   │     │     │     ├─ _mixins.scss
   │     │     │     ├─ _modal.scss
   │     │     │     ├─ _nav.scss
   │     │     │     ├─ _navbar.scss
   │     │     │     ├─ _pagination.scss
   │     │     │     ├─ _popover.scss
   │     │     │     ├─ _print.scss
   │     │     │     ├─ _progress.scss
   │     │     │     ├─ _reboot.scss
   │     │     │     ├─ _root.scss
   │     │     │     ├─ _spinners.scss
   │     │     │     ├─ _tables.scss
   │     │     │     ├─ _toasts.scss
   │     │     │     ├─ _tooltip.scss
   │     │     │     ├─ _transitions.scss
   │     │     │     ├─ _type.scss
   │     │     │     ├─ _utilities.scss
   │     │     │     ├─ _variables.scss
   │     │     │     ├─ bootstrap-grid.scss
   │     │     │     ├─ bootstrap-reboot.scss
   │     │     │     ├─ bootstrap.scss
   │     │     │     
   │     │     │     └─ vendor
   │     │     │        └─ _rfs.scss
   │     │     ├─ chart.js
   │     │     │  ├─ Admin_chart.js
   │     │     │  ├─ Chart.bundle.js
   │     │     │  ├─ Chart.bundle.min.js
   │     │     │  ├─ Chart.js
   │     │     │  └─ Chart.min.js
   │     │     ├─ datatables
   │     │     │  ├─ dataTables.bootstrap4.css
   │     │     │  ├─ dataTables.bootstrap4.js
   │     │     │  ├─ dataTables.bootstrap4.min.css
   │     │     │  ├─ dataTables.bootstrap4.min.js
   │     │     │  ├─ jquery.dataTables.js
   │     │     │  └─ jquery.dataTables.min.js
   │     │     │  ├─ js
   │     │     │  │  ├─ all.js
   │     │     │  │  ├─ all.min.js
   │     │     │  │  ├─ brands.js
   │     │     │  │  ├─ brands.min.js
   │     │     │  │  ├─ conflict-detection.js
   │     │     │  │  ├─ conflict-detection.min.js
   │     │     │  │  ├─ fontawesome.js
   │     │     │  │  ├─ fontawesome.min.js
   │     │     │  │  ├─ regular.js
   │     │     │  │  ├─ regular.min.js
   │     │     │  │  ├─ solid.js
   │     │     │  │  ├─ solid.min.js
   │     │     │  │  ├─ v4-shims.js
   │     │     │  │  └─ v4-shims.min.js
   │     │     │  ├─ less
   │     │     │  │  ├─ _animated.less
   │     │     │  │  ├─ _bordered-pulled.less
   │     │     │  │  ├─ _core.less
   │     │     │  │  ├─ _fixed-width.less
   │     │     │  │  ├─ _icons.less
   │     │     │  │  ├─ _larger.less
   │     │     │  │  ├─ _list.less
   │     │     │  │  ├─ _mixins.less
   │     │     │  │  ├─ _rotated-flipped.less
   │     │     │  │  ├─ _screen-reader.less
   │     │     │  │  ├─ _shims.less
   │     │     │  │  ├─ _stacked.less
   │     │     │  │  ├─ _variables.less
   │     │     │  │  ├─ brands.less
   │     │     │  │  ├─ fontawesome.less
   │     │     │  │  ├─ regular.less
   │     │     │  │  ├─ solid.less
   │     │     │  │  └─ v4-shims.less
   │     │     │  ├─ metadata
   │     │     │  │  ├─ categories.yml
   │     │     │  │  ├─ icons.yml
   │     │     │  │  ├─ shims.yml
   │     │     │  │  └─ sponsors.yml
   │     │     │  ├─ package.json
   │     │     │  
   │     │     ├─ jquery
   │     │     │  ├─ jquery.js
   │     │     │  ├─ jquery.min.js
   │     │     │  ├─ jquery.min.map
   │     │     │  ├─ jquery.slim.js
   │     │     │  ├─ jquery.slim.min.js
   │     │     │  └─ jquery.slim.min.map
   │     │     └─ jquery-easing
   │     │        ├─ jquery.easing.compatibility.js
   │     │        ├─ jquery.easing.js
   │     │        └─ jquery.easing.min.js
   │    
   │    
   └─ test
      └─ java
         └─ FinalProject
            └─ demo_final
               └─ DemoFinalApplicationTests.java

```
