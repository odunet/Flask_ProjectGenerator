# Flask Instant Noodle | Quick way to bootstrap full Flask project
![Flask Image](https://i.ibb.co/1nTxZkv/flask.png)

## Description
This is a simple package that enables the user to quickly bootstrap a standard Flask project.
![Sample Folder Structure](https://i.ibb.co/DQw3MjB/file-Structure.png)

## Installation
* Install virtualenv in current directory.
```bash
virtualenv venv
# 0r
python3.8 -m venv.
```

* Activate virtual environment
```bash
source venv/bin/activate
# or
source bin/activate
```

* Install Package in Current directory **(only required for first time instation in machine)**
```bash
pip install flasknoodle
```

* Generate complete Flask project template in current directory **(default project name is "server")**
```bash
flasknoodle
```

* cd into current directory (i.e. **server**)


* Install dependent packages in requirements.txt
```bash
 pip3 install -r requirements.txt
```

* Run Application
```bash
 python3 manage.py
```
##### Note: Application will run on http://127.0.0.1:5000/

## Contributing
Pull requests are welcome. Kindly ensure your commit messages are detailed enough to capture all changes done

## License
[MIT](https://choosealicense.com/licenses/mit/)
MIT License

Copyright (c) [2021] [Ayokunle Odutayo]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.