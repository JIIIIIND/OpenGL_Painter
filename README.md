# OpenGL_Painter
OpenGL을 사용한 그림판 프로그램

## Dependency
OpenGL 라이브러리가 필요합니다.

gl, glu, glut를 다운 받은 후 glut.h는 IDE의 포함 디렉터리 평가 값의 um 디렉터리 내의 gl디렉터리에 저장합니다.

glut.lib, glut32.lib는 위의 경로에서 Lib를 찾아 해당 위치에 저장합니다.

glut.dll, glut32.dll은 64비트 윈도우 사용자라면 C:\Windows\SysWOW64에, 32비트 윈도우 사용자라면 C:\Windows/System32에 저장합니다.

OpenGL 프로젝트의 추가 종속성 위치에 glut32.dll을 추가합니다.
