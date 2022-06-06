# nathanSite

- 프론트서버(Node.js) / 백엔드서버(C#.NET Core) 로 만들어진 웹 프로젝트입니다.

- 사용자가 웹에서 특정 주소(Router)를 입력하면, 프론트서버(Node.js)에서 그 Router에 맞는 화면을 클라이언트에게 보여줍니다.
- 필요한 Data를 가져오거나 저장할 경우에는 백엔드서버(C# .NET Core )에 api 요청을 날리고, api 로 값을 받은 후 클라이언트 에게 보여줍니다.

=> 왜 이렇게 하는가? => 보통 게임서버에서 사용하는 DB를 웹페이지에서도 보여주고 싶을때 ( 랭킹, 결제시스템 등 ) 이렇게 API를 요청해 데이터를 불러오는 구조로 짜면 편하기 때문입니다. 

서버처리 부분 : Server_Web_Api\WebApiManager\Controllers
클라이언트 화면 처리 부분 : Client_Web_Api\views
