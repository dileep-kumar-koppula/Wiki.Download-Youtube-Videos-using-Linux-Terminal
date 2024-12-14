# Download Youtube Videos using Linux Terminal

  1. Install Python Virtual Environment

     ```bash
     sudo apt install python3 python3-dev python-pip virtualenv -y
     ```

  2. Install
  
     ```bash
     pip install virtualenv
     ```
  
  4. Create Python Virtual Environment

  + `myenv` is my directory name. You can change whatever you like
  
     ```bash
     python -m venv myenv
     or
     virtualenv myenv
     ```

  4. Change source to Python Virtual Environment
  
     ```bash
     source myenv/bin/activate
     ```

  5. Install `yt-dlp` tool

     ```bash
     pip install -U yt-dlp
     ```

  6. Download Youtube Video

     ```bash
     yt-dlp -f "bestvideo+bestaudio" https://www.youtube.com/watch?v=Bx_X8dhANRk
     ```
  7. Deactivate Python Virtual Environment

     ```bash
     deactivate
     ```
