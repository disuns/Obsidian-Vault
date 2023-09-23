- onAttach
	- Fragment Manager에 추가될때

- onCreate
	- 생성, 일시정지 혹은 중단 후 재개 시 초기화 처리

- onCreateView
	- View를 요청할 때

- onViewCreated
	- View가 생성되었을 때

- onStart
	- 사용자에게 보여졌을 때

- onResume
	- 사용자에게 보여지고, Activity가 running 상태일때

- onPause
	- Resume 상태가 아닐때

- onStop
	- Start상태가 아닐 때

- onDestroyView
	- View를 제거 할 때

- onDestroy
	- 사용되지 않을 때

- onDetach
	- Fragment Manager에서 제거될 떄

Fragment 흐름
- FragmentStart -> onAttach -> onCreate->onCreateView -> onActivityCreate -> onStart-> onResume ->.FragmentRunning -> onPause -> onStop -> onDestroyView -> onDestroy -> onDetach -> FragmentEnd