# 3D-Tic-Tac-Toe-with-AI

```
make usual 2d tic tac toe game where llm controlling 3d world and responding to interaction with user avatar, so llm playing with user. use threejs >=0.140.0. make keyboard&mouse, real gamepad and multitouch onscreen gamepad joysticks controls for 3d move and 3d rotate, should be desktop and mobile ready. make sure not using browser alert() popups. add some sounds, but without external sound resources.

use web-llm. 
import * as webllm from "https://esm.run/@mlc-ai/web-llm";
                engine = await webllm.CreateMLCEngine(
                    "Qwen2.5-Coder-1.5B-Instruct-q4f32_1-MLC",
                    { initProgressCallback: reportProgress }
                );
engine.chat.completions.create
```
