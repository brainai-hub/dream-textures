## Intel OpenVINO x Dream Textures
### 인텔 AI PC를 활용하여 Blender에서 텍스처를 생성하는 데 사용할 수 있는 애드온입니다.
### 다음 순서대로 설치하여 사용할 수 있는 환경을 설정합니다. 
#### 관련 사이트 링크: https://github.com/intel/dream-textures-openvino

설치 프로그램 및 버전 확인하기. 다음 프로그램, 버전 환경에서 테스트 된 내용입니다.
- 블렌더 3.4.0-windows-x64.msi
- Openvino 2023.1
- Python-3.10.11-amd64.exe
- the MSFT Visual C++ Runtime: vc_redist.x86
- Dream-textures-openvino  애드온 파일 git에서 다운 받아 설치하기


Step 1. 블렌더 3.4 버전 다운받아 설치하기
- 다운로드 링크: https://mirrors.dotsrc.org/blender/release/Blender3.4/blender-3.4.0-windows-x64.msi

Step 2. Openvino 2023.1 버전 다운받아, 압축해제 후 해당 폴더에 위치시키기
- 다운로드 링크: https://storage.openvinotoolkit.org/repositories/openvino/packages/2023.1/windows/w_openvino_toolkit_windows_2023.1.0.12185.47b736f63ed_x86_64.zip
![image](https://github.com/user-attachments/assets/512cba38-01c2-47a8-9965-a3e38c8f8f07)

Step 3. Python 3.10.11 버전 다운받아 설치하기
- 다운로드 링크: https://www.python.org/ftp/python/3.10.11/python-3.10.11-amd64.exe
  * 하단의 [Add python.exe to PATH] 체크하고 설치 하기
  * 
![image](https://github.com/user-attachments/assets/18ca1394-a91e-40fb-a1b4-8d3c9775cd96)


Step 4. Microsoft Visual C++ 재배포 가능 패키지 다운받아 설치하기
- 다운로드 링크: https://aka.ms/vs/17/release/vc_redist.x86.exe

Step 5. Dream-textures-openvino  애드온 파일 다운받아, 압축 해제 후 해당 폴더에 위치시키기
- 다운로드 링크: [https://github.com/intel/dream-textures-openvino.git](https://github.com/intel/dream-textures-openvino/archive/refs/heads/main.zip)
  * C:\Program Files\Blender Foundation\Blender 3.4\3.4\scripts\addons\dream_textures

![image](https://github.com/user-attachments/assets/1a0b7024-60d7-4a24-9872-cc7b588a9317)

Step 6. Dream-textures-openvino  애드온 설치하기
- 해당 폴더로 이동한 후 install.bat 파일 실행하기

![image](https://github.com/user-attachments/assets/f6fb0843-8ec5-4a94-be5c-665ad4f0b430)

- 설치 과정에서 계속 진행을 위해 'Y' 또는 'y'를 입력한 후 엔터키로 설치를 계속 진행하기
- 그 후 모든 모델을 다운 받기 위해 '3'을 입력하고 설치를 계속 진행하기

![image](https://github.com/user-attachments/assets/016c98c7-0229-48df-b67b-f5bc668b0a84)

Step 6. w_openvino_toolkit_windows_.... 폴더의 openvino 폴더를 복사 하여 Blender...\.python_dependencies 폴더에 붙여 넣기

- **** OPENVINO MODELS SETUP COMPLETE **** 확인 하기

![image](https://github.com/user-attachments/assets/3f242c17-278c-4010-9c92-12a67d7b813b)


- 복사 폴더: C:\Program Files (x86)\Intel\w_openvino_toolkit_windows_2023.1.0.12185.47b736f63ed_x86_64\python

![image](https://github.com/user-attachments/assets/0edd37c5-7b23-43bc-9d53-7301f6085118)

- 붙여 넣기 폴더: C:\Program Files\Blender Foundation\Blender 3.4\3.4\scripts\addons\dream_textures\.python_dependencies

![image](https://github.com/user-attachments/assets/1bee89be-3303-48d0-8b37-67f7ca07afa1)

Step 7. 프로그램 실행하기

- OpenVINO 사용 환경 실행하기: C:\Program Files (x86)\Intel\w_openvino_toolkit_windows_2023.1.0.12185.47b736f63ed_x86_64>setupvars.bat

![image](https://github.com/user-attachments/assets/6b908e19-4981-4b4b-a408-841a328d08d3)


- Blender 프로그램 실행하기: C:\Program Files\Blender Foundation\Blender 3.4>blender.exe

![image](https://github.com/user-attachments/assets/3e92a9e0-7000-4e2d-8295-778e9db980e7)






