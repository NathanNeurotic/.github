<!--
IMPORTANT (THIS IS THE ACTUAL BUG IN YOUR SCREENSHOT):
GitHub parses the CONTENT INSIDE <details> as Markdown.
If lines inside <details> start with 4+ spaces, Markdown turns them into a CODE BLOCK.
That is why your placeholder comments + closing tags are printing as monospaced text.

So this version:
- Uses ZERO indentation inside <details> blocks (everything starts at column 1).
- Keeps placeholders as HTML comments, but ALSO at column 1 (so they don't become code).
- Removes extra  wrappers around the table (they can affect layout).
- Tries to keep the table a stable width with table-layout:fixed (GitHub usually allows this).
-->

<!-- =========================
     HEADER / HERO SECTION
     ========================= -->

  <a href="">
    <img src="https://github.com/user-attachments/assets/3f427f46-f343-4a43-8108-526e7f596816" />
  </a>
</p>

  <a href="https://www.chatgpt.com/">
    <img src="https://github.com/user-attachments/assets/c4e14b07-dead-4e2d-8c1b-3771e9da7d72" />
  </a>
</p>

<!-- =========================
     DESKTOP LAYOUT (3 COLUMNS)
     ========================= -->

<table width="150%" border="1" cellspacing="0" cellpadding="16" style="width:150; table-layout:fixed;">
<tr>
<th style="width:50%; text-align:center;">--------------- Outbound -----------------</th>
<th style="width:50%; text-align:center;">----------------- Local ------------------</th>
<th style="width:50%; text-align:center;">---------------- Network -----------------</th>
</tr>

<tr>
<td valign="top" style="width:33.3%; text-align:center;">
<details>
<summary><b>--run</b></summary>

<a href="https://aistudio.google.com/"><img width="50" height="50" alt="aistudio" src="https://github.com/user-attachments/assets/165ce3bd-ebf8-4518-8270-c6207666c4a5" /></a>
<a href="https://www.bing.com/"><img width="50" height="50" alt="bing-color" src="https://github.com/user-attachments/assets/ffce4c98-9c34-4145-8a95-49519d9b81f0" /></a>
<a href="https://chatgpt.com/codex"><img width="50" height="50" alt="openai" src="https://github.com/user-attachments/assets/34d7dde5-389a-4ea6-8f74-c5bae1c0a178" /></a><br>
<a href="https://www.deepl.com/"><img width="50" height="50" alt="deepl-color" src="https://github.com/user-attachments/assets/ab15ada7-6707-406a-b8ae-fd56a36c5a2b" /></a>
<a href="https://www.deepseek.com/"><img width="50" height="50" alt="deepseek-color" src="https://github.com/user-attachments/assets/83ff4caa-a3fb-4dd0-8578-1e9b30886397" /></a>
<a href="https://gemini.google.com/"><img width="50" height="50" alt="gemini-color" src="https://github.com/user-attachments/assets/6f094dbc-6eee-48a8-b0b8-b076dcef79c2" /></a><br>
<a href="https://github.com/"><img width="50" height="50" alt="github" src="https://github.com/user-attachments/assets/0f03ae92-7df7-4117-a07b-2b919f057c9b" /></a>
<a href="https://github.com/features/copilot"><img width="50" height="50" alt="githubcopilot" src="https://github.com/user-attachments/assets/30bf56ec-b9a5-4372-9892-6b8eaba53886" /></a>
<a href="https://copilot.microsoft.com/"><img width="50" height="50" alt="copilot-color" src="https://github.com/user-attachments/assets/700a96dd-773d-49ce-9676-fad3d82299c0" /></a><br>
<a href="https://grok.com/"><img width="50" height="50" alt="grok" src="https://github.com/user-attachments/assets/fcb0f45e-edf2-4c92-a34f-38a62ff9a9c1" /></a>
<a href="https://hailuoai.com/"><img width="50" height="50" alt="hailuo-color" src="https://github.com/user-attachments/assets/6278e6b0-f8d3-4847-aecd-f247ea3266dc" /></a>
<a href="https://huggingface.co/"><img width="50" height="50" alt="huggingface-color" src="https://github.com/user-attachments/assets/1f53102a-08b2-41e1-807d-72248c7a01a5" /></a><br>
<a href="https://hunyuan.tencent.com/"><img width="50" height="50" alt="hunyuan-color" src="https://github.com/user-attachments/assets/acc4f98b-7408-4464-8ca2-a18c9fd76078" /></a>
<a href="https://jina.ai/"><img width="50" height="50" alt="jina" src="https://github.com/user-attachments/assets/a5ff55c6-ff8b-4c82-a6d5-569f23c7a948" /></a>
<a href="https://klingai.com/"><img width="50" height="50" alt="kling-color" src="https://github.com/user-attachments/assets/d5416ca8-52e5-491d-9eb3-04d4757ce7e4" /></a><br>
<a href="https://lmstudio.ai/"><img width="50" height="50" alt="lmstudio" src="https://github.com/user-attachments/assets/84d895fb-ba0f-4b30-99f0-930a454a7768" /></a>
<a href="https://manus.im/"><img width="50" height="50" alt="manus" src="https://github.com/user-attachments/assets/9965edf4-04df-4ab0-a6ff-bd19139b712d" /></a>
<a href="https://mastra.ai/"><img width="50" height="50" alt="mastra" src="https://github.com/user-attachments/assets/938cc629-b86e-413b-9f30-5c9652dde9d7" /></a><br>
<a href="https://about.meta.com/"><img width="50" height="50" alt="meta-color" src="https://github.com/user-attachments/assets/ebf8c4dd-2b69-40f1-b160-7dbc27b23406" /></a>
<a href="https://www.meta.ai/"><img width="50" height="50" alt="metaai-color" src="https://github.com/user-attachments/assets/8250e043-0898-4d9c-8fd7-6a13b32d1a86" /></a>
<a href="https://www.microsoft.com/"><img width="50" height="50" alt="microsoft-color" src="https://github.com/user-attachments/assets/73c82fd4-cc3c-4718-91d6-0b57130df5b0" /></a><br>
<a href="https://www.minimax.io/"><img width="50" height="50" alt="minimax-color" src="https://github.com/user-attachments/assets/4ba9ec0a-fd71-4287-adab-5d8734c56322" /></a>
<a href="https://notebooklm.google/"><img width="50" height="50" alt="notebooklm" src="https://github.com/user-attachments/assets/4bf6f6fb-ec97-4994-bc4e-95e2e97e8b25" /></a>
<a href="https://www.notion.so/"><img width="50" height="50" alt="notion" src="https://github.com/user-attachments/assets/50c72dbf-9012-4ced-ad07-6d08008cee20" /></a><br>
<a href="https://ollama.com/"><img width="50" height="50" alt="ollama" src="https://github.com/user-attachments/assets/3ca5f33c-4fee-4cd5-9487-5bb410bb5024" /></a>
<a href="https://www.perplexity.ai/"><img width="50" height="50" alt="perplexity-color" src="https://github.com/user-attachments/assets/9e822a2a-4a91-49b6-916f-d798a654e30e" /></a>
<a href="https://sora.com/"><img width="50" height="50" alt="sora-color" src="https://github.com/user-attachments/assets/47624302-c973-42ed-b19f-765f62a99164" /></a><br>
<a href="https://suno.com/"><img width="50" height="50" alt="suno" src="https://github.com/user-attachments/assets/39a86db9-9f74-45e7-8fd7-1ee4f798a1ca" /></a>
<a href="https://www.udio.com/"><img width="50" height="50" alt="udio-color" src="https://github.com/user-attachments/assets/2be6963e-e87c-4069-8f75-a62c57087f6f" /></a>
<a href="https://yuanbao.tencent.com/"><img width="50" height="50" alt="yuanbao-color" src="https://github.com/user-attachments/assets/aaae69ee-6637-47b9-9628-3002a2deae59" /></a><br>

</details>
</td>

<td valign="top" style="width:33.3%;">
<details>
<summary><b>--help</b></summary>

<a href="Mastering_AI_Without_Overthinking_It.md.md"><img alt="Guide 1" src="https://github.com/user-attachments/assets/a963cb7c-686e-44c4-902d-648a201b1947" width="160" height="40" /></a>

<!-- --help PLACEHOLDERS (copy/paste + fill in) -->
<!-- <a href="PATH_TO_YOUR_GUIDE_2.md"><img alt="Guide 2" src="https://github.com/user-attachments/assets/YOUR_BUTTON_ASSET_ID_2" width="160" height="40" /></a> -->
<!-- <a href="PATH_TO_YOUR_GUIDE_3.md"><img alt="Guide 3" src="https://github.com/user-attachments/assets/YOUR_BUTTON_ASSET_ID_3" width="160" height="40" /></a> -->
<!-- <a href="PATH_TO_YOUR_GUIDE_4.md"><img alt="Guide 4" src="https://github.com/user-attachments/assets/YOUR_BUTTON_ASSET_ID_4" width="160" height="40" /></a> -->
</details>
</td>

<td valign="top" style="width:33.3%;">
<details>
<summary><b>--connect</b></b></summary>
<a href="https://discord.gg/KRtqWeNdfC"><img src="https://img.shields.io/discord/1256458065834676244?style=flat&logo=discord&logoColor=7289DA&label=Discord&labelColor=6A0DAD&color=5865F2" alt="Discord"></a></p>
<!-- COLUMN 3 PLACEHOLDERS (copy/paste + fill in) -->
<!-- <a href="https://LOCAL_TOOL_OR_RESOURCE_URL"><img width="50" height="50" alt="local-tool" src="https://github.com/user-attachments/assets/YOUR_ASSET_ID" /></a> -->
<!-- <a href="PATH_TO_LOCAL_DOC.md"><img width="160" height="40" alt="Local Doc" src="https://github.com/user-attachments/assets/YOUR_BUTTON_ASSET_ID" /></a> -->
</details>
</td>
</tr>
</table>
<table width="100%" border="1" cellspacing="0" cellpadding="16" style="width:100%; table-layout:fixed;">
<tr>
<th style="width:100%; text-align:center;"><details>
<summary><b>Mobile Friendly</b><i>(Verticle Stacked Layout)</i></summary>
<b>---------- Outbound ----------</b>
<details>
<summary><b>--run</b></summary>
<a href="https://aistudio.google.com/"><img width="50" height="50" alt="aistudio" src="https://github.com/user-attachments/assets/165ce3bd-ebf8-4518-8270-c6207666c4a5" /></a>
<a href="https://www.bing.com/"><img width="50" height="50" alt="bing-color" src="https://github.com/user-attachments/assets/ffce4c98-9c34-4145-8a95-49519d9b81f0" /></a>
<a href="https://chatgpt.com/codex"><img width="50" height="50" alt="openai" src="https://github.com/user-attachments/assets/34d7dde5-389a-4ea6-8f74-c5bae1c0a178" /></a>
<a href="https://www.deepl.com/"><img width="50" height="50" alt="deepl-color" src="https://github.com/user-attachments/assets/ab15ada7-6707-406a-b8ae-fd56a36c5a2b" /></a>
<a href="https://www.deepseek.com/"><img width="50" height="50" alt="deepseek-color" src="https://github.com/user-attachments/assets/83ff4caa-a3fb-4dd0-8578-1e9b30886397" /></a>
<a href="https://gemini.google.com/"><img width="50" height="50" alt="gemini-color" src="https://github.com/user-attachments/assets/6f094dbc-6eee-48a8-b0b8-b076dcef79c2" /></a>
<a href="https://github.com/"><img width="50" height="50" alt="github" src="https://github.com/user-attachments/assets/0f03ae92-7df7-4117-a07b-2b919f057c9b" /></a>
<a href="https://github.com/features/copilot"><img width="50" height="50" alt="githubcopilot" src="https://github.com/user-attachments/assets/30bf56ec-b9a5-4372-9892-6b8eaba53886" /></a>
<a href="https://copilot.microsoft.com/"><img width="50" height="50" alt="copilot-color" src="https://github.com/user-attachments/assets/700a96dd-773d-49ce-9676-fad3d82299c0" /></a>
<a href="https://grok.com/"><img width="50" height="50" alt="grok" src="https://github.com/user-attachments/assets/fcb0f45e-edf2-4c92-a34f-38a62ff9a9c1" /></a>
<a href="https://hailuoai.com/"><img width="50" height="50" alt="hailuo-color" src="https://github.com/user-attachments/assets/6278e6b0-f8d3-4847-aecd-f247ea3266dc" /></a>
<a href="https://huggingface.co/"><img width="50" height="50" alt="huggingface-color" src="https://github.com/user-attachments/assets/1f53102a-08b2-41e1-807d-72248c7a01a5" /></a>
<a href="https://hunyuan.tencent.com/"><img width="50" height="50" alt="hunyuan-color" src="https://github.com/user-attachments/assets/acc4f98b-7408-4464-8ca2-a18c9fd76078" /></a>
<a href="https://jina.ai/"><img width="50" height="50" alt="jina" src="https://github.com/user-attachments/assets/a5ff55c6-ff8b-4c82-a6d5-569f23c7a948" /></a>
<a href="https://klingai.com/"><img width="50" height="50" alt="kling-color" src="https://github.com/user-attachments/assets/d5416ca8-52e5-491d-9eb3-04d4757ce7e4" /></a>
<a href="https://lmstudio.ai/"><img width="50" height="50" alt="lmstudio" src="https://github.com/user-attachments/assets/84d895fb-ba0f-4b30-99f0-930a454a7768" /></a>
<a href="https://manus.im/"><img width="50" height="50" alt="manus" src="https://github.com/user-attachments/assets/9965edf4-04df-4ab0-a6ff-bd19139b712d" /></a>
<a href="https://mastra.ai/"><img width="50" height="50" alt="mastra" src="https://github.com/user-attachments/assets/938cc629-b86e-413b-9f30-5c9652dde9d7" /></a>
<a href="https://about.meta.com/"><img width="50" height="50" alt="meta-color" src="https://github.com/user-attachments/assets/ebf8c4dd-2b69-40f1-b160-7dbc27b23406" /></a>
<a href="https://www.meta.ai/"><img width="50" height="50" alt="metaai-color" src="https://github.com/user-attachments/assets/8250e043-0898-4d9c-8fd7-6a13b32d1a86" /></a>
<a href="https://www.microsoft.com/"><img width="50" height="50" alt="microsoft-color" src="https://github.com/user-attachments/assets/73c82fd4-cc3c-4718-91d6-0b57130df5b0" /></a>
<a href="https://www.minimax.io/"><img width="50" height="50" alt="minimax-color" src="https://github.com/user-attachments/assets/4ba9ec0a-fd71-4287-adab-5d8734c56322" /></a>
<a href="https://notebooklm.google/"><img width="50" height="50" alt="notebooklm" src="https://github.com/user-attachments/assets/4bf6f6fb-ec97-4994-bc4e-95e2e97e8b25" /></a>
<a href="https://www.notion.so/"><img width="50" height="50" alt="notion" src="https://github.com/user-attachments/assets/50c72dbf-9012-4ced-ad07-6d08008cee20" /></a>
<a href="https://ollama.com/"><img width="50" height="50" alt="ollama" src="https://github.com/user-attachments/assets/3ca5f33c-4fee-4cd5-9487-5bb410bb5024" /></a>
<a href="https://www.perplexity.ai/"><img width="50" height="50" alt="perplexity-color" src="https://github.com/user-attachments/assets/9e822a2a-4a91-49b6-916f-d798a654e30e" /></a>
<a href="https://sora.com/"><img width="50" height="50" alt="sora-color" src="https://github.com/user-attachments/assets/47624302-c973-42ed-b19f-765f62a99164" /></a>
<a href="https://suno.com/"><img width="50" height="50" alt="suno" src="https://github.com/user-attachments/assets/39a86db9-9f74-45e7-8fd7-1ee4f798a1ca" /></a>
<a href="https://www.udio.com/"><img width="50" height="50" alt="udio-color" src="https://github.com/user-attachments/assets/2be6963e-e87c-4069-8f75-a62c57087f6f" /></a>
<a href="https://yuanbao.tencent.com/"><img width="50" height="50" alt="yuanbao-color" src="https://github.com/user-attachments/assets/aaae69ee-6637-47b9-9628-3002a2deae59" /></a>
</details>
<b>---------- Local ----------</b>
<details>
<summary><b>--help</b></summary>
<a href="Mastering_AI_Without_Overthinking_It.md.md"><img alt="Guide 1" src="https://github.com/user-attachments/assets/a963cb7c-686e-44c4-902d-648a201b1947" width="160" height="40" /></a>
</details>
<b>---------- Network ----------</b>
<details>
<summary><b>--connect</b></summary>
<a href="https://discord.gg/KRtqWeNdfC"><img src="https://img.shields.io/discord/1256458065834676244?style=flat&logo=discord&logoColor=7289DA&label=Discord&labelColor=6A0DAD&color=5865F2" alt="Discord"></a>
</details></th>
</tr
</details>
</p>
