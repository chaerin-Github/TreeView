# TreeView 첫 실행화면
![image](https://user-images.githubusercontent.com/105805974/207596882-6e171a16-7baa-42ed-9eaa-66d6426eee80.png)



# Tree.xaml
![image](https://user-images.githubusercontent.com/105805974/207598568-bd444f88-3d83-49d9-8b3f-439070fabf04.png)
![image](https://user-images.githubusercontent.com/105805974/207599039-45496c93-a5b8-4c06-84a2-9b0df6834ede.png)

WorkDocuments의 하위노드 4개를 만들고 Personal Documents에 Home Remodel 속성을 만들고 하위노드를 4개 만들었다.
TreeView라는 버튼을 만들어 버튼을 클릭했을때 하위노드들이 사라지도록 기능을 추가하였다.

# Tree.xaml.cpp
![image](https://user-images.githubusercontent.com/105805974/207599548-97b79a81-7b98-470d-9004-e1a090af29a2.png)
트리뷰의 하위 노드 부분이 트리뷰 버튼을 누르게 되면 목록들이 사라지게 된다.(기존 소스코드에서 추가한부분)

# Tree.xaml.h
![image](https://user-images.githubusercontent.com/105805974/207601129-f0a8708c-9431-4245-bfe8-75d12a7c860f.png)

# TreeView 결과화면
![image](https://user-images.githubusercontent.com/105805974/207601593-8026d9da-98e6-4965-b602-8f1ab5642649.png)

TreeView의 노드를 모두 체크한 모습

![image](https://user-images.githubusercontent.com/105805974/207601755-360f4ebe-f268-456a-9a38-161b7baa9bbb.png)

![image](https://user-images.githubusercontent.com/105805974/207602197-b192f1ac-d298-41e5-a2d7-d27db390f1d2.png)

트리뷰버튼을 눌렀을때 결과화면의 모습 



실행결과 유튜브 링크: https://www.youtube.com/watch?v=uNqbI1G-nyM

참고문헌: https://github.com/microsoft/WinUI-Gallery/blob/main/WinUIGallery/ControlPages/TreeViewPage.xaml
          
