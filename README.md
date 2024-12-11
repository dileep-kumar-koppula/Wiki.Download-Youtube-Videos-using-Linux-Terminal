# Download Youtube Videos using Linux Terminal
  1.Create Python Virtual Environment
    ```bash
    python -m venv myenv
    ```
  2.Change source to Python Virtual Environment
    ```bash
    source myenv/bin/activate
    ```
  3.Install `yt-dlp` tool
    ```bash
    pip install -U yt-dlp
    ```
  4.Download Youtube Video
    ```bash
    yt-dlp -f "bestvideo+bestaudio" https://www.youtube.com/watch?v=Bx_X8dhANRk
    ```
