# Unity GPU Particle

Unityによる、GPU Particle Systemです。OSX(not DX11)でも、動きます。

RenderTextureに、パーティクルの速度、位置、色情報を格納。

テクスチャは、Shaderにより、アップデートしています。

n*n個のパーティクルをRenderTextureにより制御しています。

Unity標準のParticleSystemと比較し、より多くのParticleを少ない負荷で処理します。

DX11や、他のモダンな3D APIの使用の場合は、ComputeShaderを使用したこちらの[GPU-Particle](https://github.com/sugi-cho/GPU-Particle)の方法がおススメです！

## Images

### CurlNoise
![](img/scene1.png) 

### Particle Emitter
![](img/scene2.png)

### Screen Space Particle Collision
![](img/scene3.png)

[Youtube](https://youtu.be/E81EVRG0SlU)
