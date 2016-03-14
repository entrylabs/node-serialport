### 빌드 방법
node-pre-gyp configure
node-pre-gyp build

32비트
node-pre-gyp rebuild --target_arch=ia32  --target=0.36.10  --target_platform=win32  --runtime=electron  --dist-url=https://atom.io/download/atom-shell

64비트
node-pre-gyp rebuild  --target=0.36.10  --target_platform=win32  --runtime=electron  --dist-url=https://atom.io/download/atom-shell
