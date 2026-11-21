# Drama Script Writer

A Claude skill that writes vertical short drama scripts, ready for [Higgsfield Short Drama](https://higgsfield.ai/short-drama).

- One question at a time, with numbered options. Reply with a number, a few words, or "choose for me".
- A shock in the first 2 seconds, a twist in every scene, and a cliffhanger at the end of every episode.
- Built around Higgsfield's limits: ages for every character, at most 8 characters, 4 locations and 4 props, and short on-screen text so it renders cleanly.
- Original stories only. It borrows moods, never plots.

## Install

1. Download **[short-drama-writer.zip](https://github.com/matt-j-penny/drama-script-writer/releases/latest/download/short-drama-writer.zip)**.
2. In Claude, go to **Settings → Capabilities → Skills**, click **Upload**, and pick the zip.
3. Start a new chat with:
   ```
   Use the short drama skill. I want to make a short drama.
   ```

## Generate the episode

- **In Claude:** connect Higgsfield from [higgsfield.ai/mcp](https://higgsfield.ai/mcp), then in the same chat:
  ```
  Use Higgsfield to run /short-drama. Generate a short drama based on the final script above.
  ```
- **On the website:** save the script as a .txt and upload it at [higgsfield.ai/short-drama](https://higgsfield.ai/short-drama).
