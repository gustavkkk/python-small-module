### Meta

  - [ ] [how to design large-scale systems](https://github.com/donnemartin/system-design-primer)
  
  - [ ] [interactive-coding-challenges](https://github.com/donnemartin/interactive-coding-challenges)
  
  - [ ] [data-science-ipython-notebooks](https://github.com/donnemartin/data-science-ipython-notebooks)
  
  - [ ] [game-programmer](https://github.com/miloyip/game-programmer)

### News

  - [ ] [haxor-news](https://github.com/donnemartin/haxor-news)
  
        $ pip install haxor-news
        $ haxor-news
        haxor> hn top
        haxor> hn show 20
        
  - [ ] [HackerNewsAPI](https://github.com/karan/HackerNewsAPI/)     
       
          
### Docker

  - [ ] [docker_practice](https://github.com/yeasy/docker_practice)
  
### Under-Check

  - [ ] [geekcomputers](https://github.com/geekcomputers/Python)
  
  - [ ] [example-code](https://github.com/fluentpython/example-code)
  
  - [ ] [python-patterns](https://github.com/faif/python-patterns)
  
  - [ ] [python-algorithms](https://github.com/keon/algorithms)
  
  - [ ] [Zappa](https://github.com/Miserlou/Zappa)

### [Binding](https://wiki.python.org/moin/IntegratingPythonWithOtherLanguages)

  - [ ] [c-in-python](https://stackoverflow.com/questions/13990317/generate-python-bindings-what-methods-programs-to-use)
  
       keyword :  wrapper,[extending](https://docs.python.org/3/extending/extending.html),binding,calling,[integrating](https://wiki.python.org/moin/IntegratingPythonWithOtherLanguages),[embedding](https://docs.python.org/2/extending/embedding.html),python,c++ 
        
      * [ctypes](https://docs.python.org/2/library/ctypes.html)
      * [swig](https://github.com/swig/swig)[tutorial](http://www.swig.org/tutorial.html)
      * [boost.python](http://www.boost.org/doc/libs/1_49_0/libs/python/doc/)
      * [cython]()
      
  - [ ] [ipc](http://zguide.zeromq.org/)
      
      * [zeromq:one and only ipc between python and c++](https://github.com/zeromq/pyzmq)
      * [zguide](https://github.com/booksbyus/zguide/tree/master/examples)
      * [libzmq](https://github.com/zeromq/libzmq)
      
      * [clif](https://github.com/google/clif)
      
  - [x] [python-in-c](https://github.com/gustavkkk/embedding-python-in-c)
  
  - [ ] [.Net in python](https://github.com/pythonnet/pythonnet)
  
  - [ ] [hdf5 in python](https://github.com/h5py/h5py)
  
### Conversion

  - [x] [chinese2Integer](https://github.com/gustavkkk/python-small-module/blob/master/chn2int.py)
  
  - [ ] [xlsx2csv](https://github.com/dilshod/xlsx2csv)
  
  - [ ] [csv2sqlite](https://github.com/rasbt/python_reference/blob/master/useful_scripts/large_csv_to_sqlite.py) : [](https://github.com/simonw/csvs-to-sqlite)
  
  - [ ] [xls2db](https://github.com/jfhbrook/xls2db)
  
  - [x] [xls2sqlite](https://github.com/bermau/xls2sqlite)
  
  - [ ] [sqlite2xls](https://github.com/flow-phys/sqlite2xls/blob/master/sqlite2xls)
  
  - [ ] [cpp2python](https://github.com/andreikop/cpp2python)
  
  - [ ] [python2android](https://github.com/kivy/python-for-android)
  
  - [ ] [shell-command-in-python](https://github.com/amoffat/sh)
  
  - [ ] [python-dict2xml](https://github.com/delfick/python-dict2xml)
  
  - [ ] [xmltodict](https://github.com/martinblech/xmltodict) : [XML2Dict](https://github.com/mcspring/XML2Dict)

### Scraping

  - [ ] [](https://github.com/scrapy/scrapy)
  
        $ pip install scrapy

  - [ ] [you-get: video,image,audio](https://github.com/soimort/you-get)
        
        $ pip install you-get
        $ you-get 'https://www.youtube.com/watch?v=jNQXAC9IVRw'
    
  - [ ] [youtube-dl:video](https://github.com/rg3/youtube-dl)
      
        $ pip install --upgrade youtube-dl
  
  - [ ] [pyspider](https://github.com/binux/pyspider)
  
### Network

  - [ ] [httpie:interact-with-webserver-using-CLI](https://github.com/jakubroztocil/httpie)
  
        $ pip install --upgrade httpie
        $ http baidu.com
        submitting
        $ http -f POST example.org hello=World
        uploading
        $ http example.org < file.json
        downloading
        $ http example.org/file > file
        $ http --download example.org/file
        .....
        
  - [ ] [requests](https://github.com/requests/requests)
  
  - [ ] [shadowsocks:bypass-firewall](https://github.com/shadowsocks/shadowsocks/tree/master)
  
  - [ ] [fabric:remote-execution](https://github.com/fabric/fabric)

### DataBase

  - [ ] [sqlmap:Automatic SQL injection and database takeover tool ](https://github.com/sqlmapproject/sqlmap)
  
### Auto

  - [ ] [home](https://github.com/home-assistant/home-assistant)
  
        $ pip install homeassistant
        $ pip install xml2dict
        $ hass --open-ui
        http://192.168.0.8:8123
  
  - [x] [wechat](https://github.com/littlecodersh/ItChat)
  
        import itchat
        itchat.auto_login()
        author = itchat.search_friends(nickName='田')[0]
        author.send('greeting, littlecoder!')
   
  - [ ] [QQ](https://github.com/pandolia/qqbot)
  
  - [ ] [twitter](https://github.com/tweepy/tweepy)
  
  - [x] email
  
     * [gmail-receiver](https://github.com/charlierguo/gmail):[gmail-sender](https://github.com/paulchakravarti/gmail-sender)
     
            import gmail
            from gmail import Gmail
            g = gmail.login(username, password)
            
     * [mailthon](https://github.com/eugene-eeo/mailthon)
     
            from mailthon import postman, email
            p = postman(host='smtp.outlook.com', auth=('username', 'password'))
            r = p.send(email(
                content=u'<p>Hello 世界</p>',
                subject='Hello world',
                sender='Pi<gustav0125@outlook.com>',
                receivers=['doe@163.com']))
            assert r.ok
     
  - [x] [ui](https://gfycat.com/PointlessSimplisticAmericanquarterhorse)
  
         import pyautogui
         import time
         pyautogui.position()
         while True:
           time.sleep(0.1)
           pyautogui.click(15,42)
           
  - [ ] [slacker](https://github.com/os/slacker)
  
      * [](https://github.com/slackapi/python-slackclient)
      
  - [ ] [skype](https://github.com/Skype4Py/Skype4Py)
  
          
  
  - [ ] [chrome-db](https://github.com/MonroCoury/Forensic-Tools)
  
  - [ ] Amazon
      * [boto](https://github.com/boto/boto)
      * [aws-cli](https://github.com/aws/aws-cli)
  
  - [ ] [Trading](https://github.com/quantopian/zipline) : [tushare:historical-data-from-chinese-stock](https://github.com/waditu/tushare)
  
  - [ ] [弹幕](https://github.com/littlecodersh/danmu)
  
  - [ ] [webbrowser](https://github.com/SeleniumHQ/selenium)
  
  
### Data & Time

  - [ ] [pendulum](https://github.com/sdispater/pendulum)
  
  - [ ] [arrow](https://github.com/crsmithdev/arrow)
  
  - [ ] [maya](https://github.com/kennethreitz/maya)
  
### File/Dir Processing
  
  - [ ] files with specific pattern in a folder
  
        glob.glob(subpath_+'\\*'+pattern+'*.j*pg')
  
  - [x] files including one-sub-dir or not
  
        glob.iglob(subpath_+'\\**\\' + '*'+category+'*.j*pg', recursive=True)
  
 ### Utility
 
  - [x] [magic-wormhole:file-send-receiver](https://github.com/warner/magic-wormhole)
   
        $ pip install magic-wormhole
        
        sender$ wormhole send README.md
              Sending 7924 byte file named 'README.md'
              On the other computer, please run: wormhole receive
              Wormhole code is: 7-crossover-clockwork
        receiver$ wormhole receive
                Enter receive wormhole code: 7-crossover-clockwork
                Receiving file (7924 bytes) into: README.md
                ok? (y/n): y
  - [ ] [maybe:check-before-done](https://github.com/p-e-w/maybe)
  
        $ pip install maybe
        
  - [ ] [howdoi:programming-grammar-check](https://github.com/gleitz/howdoi)
  
        $ pip install howdoi
        opening vpn
        $ howdoi dictionary insert python
        $ howdoi network test bash
        
  - [ ] [glances:An-eye-on-your-system](https://github.com/nicolargo/glances)
  
        $ pip install glances
        $ pip install pysnmp
        $ glances
        
  - [x] [thefuck:Auto-Correcting-Command](https://github.com/nvbn/thefuck)
  
        $ pip install thefuck
  
  - [ ] [fabric:Shell-Command-On-Multi-Servers-Same-Time](https://github.com/fabric/fabric)
  
  - [ ] [fire:Automatically-generating-CLIs-from-any-Python-Object](https://github.com/google/python-fire)
  
        import fire
        class Calculator(object):
          """A simple calculator class."""
          def double(self, number):
            return 2 * number
        if __name__ == '__main__':
          fire.Fire(Calculator)
        
        $ python calculator.py double 10  # 20
        $ python calculator.py double --number=15  # 30
       
  - [ ] [mackup:Back-Up-Application-Setting-Into-DropBox](https://github.com/lra/mackup)
  
  - [ ] [mkdocs:Make-Project-Docs](https://github.com/mkdocs/mkdocs)
  
  - [ ] [BossSensor:Hide-screen-when-boss-is-approaching](https://github.com/Hironsan/BossSensor)
  
  - [ ] [moviepy:Video-Editing](http://zulko.github.io/moviepy/)
  
  - [ ] [legit:Git-for-Humans](https://github.com/kennethreitz/legit)
  
  - [ ] [wttr:weather](https://github.com/chubin/wttr.in)
  
  - [ ] [voltron:reversing-tool](https://github.com/snare/voltron)
  
  - [ ] [webpage2png](https://github.com/paulhammond/webkit2png)
  
        $ pip install webkit2png
        webkit2png http://www.google.com/
  
  - [ ] [check-security-state-of-your-PC](https://github.com/chipsec/chipsec
  
  - [ ] [fabric:remote-ssh-](https://github.com/fabric/fabric)
  
  - [ ] [yapf:A-formatter-for-Python-files](https://github.com/google/yapf)
  
  - [ ] [speedtest-cli:internet-bandwidth-testing-cmd](https://github.com/sivel/speedtest-cli)
  
        $ pip install speedtest-cli
        $ speedtest-cli
  
 ### [Python in C++](https://www.coveros.com/calling-python-code-from-c/)
 
 
 ### [Create-Project](https://github.com/ofek/hatch)
 
 ### [Distribution](https://stackoverflow.com/questions/14165398/a-good-python-to-exe-compiler)
 
  - [x] [pyinstaller](https://github.com/pyinstaller/pyinstaller) : [how2exclude](https://stackoverflow.com/questions/17034434/how-to-remove-exclude-modules-and-files-from-pyinstaller) : [how-to-decrease-exe-size: pandas-conda2pip](https://stackoverflow.com/questions/43886822/pyinstaller-with-pandas-creates-over-500-mb-exe) : [pyqt5-exe-making](https://winterj.me/pyinstaller/) : [how-to-exclude](https://github.com/pyinstaller/pyinstaller/issues/1239)
  
        This is the one and only choice for tensorflow-based application distribution and works great. But, you have to install python using brew not anaconda for Mac.
        
        $ pyinstaller  --onefile --windowed xxx.py
        # the following code help decreasing pkg size
        Analysis(..., excludes=['_gtkagg', '_tkagg', 'bsddb', 'curses', 'pywin.debugger', 'pywin.debugger.dbgcon', 'pywin.dialogs', 'tcl', 'Tkconstants', 'Tkinter', 'PyQt5','zmq'], ..)
        # the following code after Analyssi(...) help pandas works while using pyinstaller
        # it's better to use pip pandas than conda pandas for pkg size. conda pandas needs more than 400MB extra weight.
        def get_pandas_path():
        import pandas
        pandas_path = pandas.__path__[0]
        return pandas_path

        dict_tree = Tree(get_pandas_path(), prefix='pandas', excludes=["*.pyc"])
        a.datas += dict_tree
        a.binaries = filter(lambda x: 'pandas' not in x[0], a.binaries)
        
        $ pyinstaller xxx.spec
        
  - [x] [cx_Freeze](https://github.com/anthony-tuininga/cx_Freeze/blob/master/doc/distutils.rst)
  
        import sys
        from cx_Freeze import setup, Executable
        build_exe_options = {"packages": ["os"], "excludes": ["tkinter"]}
        base = None
        if sys.platform == "win32":
            base = "Win32GUI"

        setup(  name = "guifoo",
                version = "0.1",
                description = "My GUI application!",
                options = {"build_exe": build_exe_options},
                executables = [Executable("guifoo.py", base=base)])
 
  ### [Packaging and Distribution](https://github.com/storborg/python-packaging/blob/master/index.rst) : [pypa](https://github.com/pypa/python-packaging-user-guide)
  
  - [ ] [Use-Hatch](https://github.com/ofek/hatch)
  
  - [ ] [setup.py](https://github.com/kennethreitz/setup.py)
  
  ### Dependency-Check
  
  - [ ] [pipdeptree](https://github.com/naiquevin/pipdeptree)
  
        $ pipdeptree
        $ pipdeptree --reverse --packages itsdangerous,gnureadline
        #$ pip freeze
        #$ conda env list
  
  ### GUI 
  - [ ] [pyqt]()
  
  - [ ] [kivy]()

  ### Bot
  - [ ] ChatBot
    
      * [ChatterBot](https://github.com/gunthercox/ChatterBot)
      
  - [ ] WeChat
      
      * [WeixinBot](https://github.com/Urinx/WeixinBot)

  ### 3D
  
  - [ ] [SpaceshipGenerator:with-Random-Seed](https://github.com/a1studmuffin/SpaceshipGenerator)
  
  ### Guide
  
   [python-guide](https://github.com/kennethreitz/python-guide)
   
  ### Fake Data Generator
  
  - [x] [faker](https://github.com/joke2k/faker)
   
        from faker import Faker
        fake = Faker('en_US')
        fake.name()
        # 'Lucy Cechtelar'
        fake.address()
        # "426 Jordy Lodge
        #  Cartwrightshire, SC 88120-6700"
        fake.text()
        # Sint velit eveniet. Rerum atque repellat voluptatem quia rerum. Numquam excepturi
        # beatae sint laudantium consequatur. Magni occaecati itaque sint et sit tempore. Nesciunt
        # amet quidem. Iusto deleniti cum autem ad quia aperiam.
        # A consectetur quos aliquam. In iste aliquid et aut similique suscipit. Consequatur qui
        # quaerat iste minus hic expedita. Consequuntur error magni et laboriosam. Aut aspernatur
        # voluptatem sit aliquam. Dolores voluptatum est.
        # Aut molestias et maxime. Fugit autem facilis quos vero. Eius quibusdam possimus est.
        # Ea quaerat et quisquam. Deleniti sunt quam. Adipisci consequatur id in occaecati.
        # Et sint et. Ut ducimus quod nemo ab voluptatum.
   
  - [ ] [mimesis](https://github.com/lk-geimfari/mimesis)
  
        from mimesis import Personal
        from mimesis.enums import Gender
        person = Personal('en')
        person.full_name(gender=Gender.FEMALE)
        person.occupation()
        templates = ['U_d', 'U-d', 'l_d', 'l-d']
        for template in templates:
          person.username(template=template)
        Personal('de').full_name()
        from mimesis import Generic
        from mimesis.enums import TLDType
        g = Generic('es')
        g.datetime.month()
        g.food.fruit()
        g.internet.top_level_domain(TLDType.GEOTLD)
 
  - [ ] [gen_db.py](https://bitbucket.org/frank0125/biddingdocument/src/8f034d22a750c5e08b593d79df7808fcf1f030f9/processing/gen_db.py?at=master&fileviewer=file-view-default)
  
  ### Cryptography

  - [x] [cryptography](https://github.com/pyca/cryptography)
  
        from cryptography.fernet import Fernet
        # Put this somewhere safe!
        key = Fernet.generate_key()
        f = Fernet(key)
        token = f.encrypt(b"A really secret message. Not for prying eyes.")
        token
        '...'
        f.decrypt(token)
        'A really secret message. Not for prying eyes.'
  

  ### Debug
  
  - [ ] [check-memory-usage-python-code-per-line](https://github.com/pythonprofilers/memory_profiler)

# Data Science
  ### Data Visualization
  
  - [ ] [d3-Gallery](https://github.com/d3/d3/wiki/Gallery)
  
  - [ ] [bokeh](https://github.com/bokeh/bokeh)
  
  - [ ] [altair](https://github.com/altair-viz/altair)
  
  - [ ] [d3py](https://github.com/mikedewar/d3py)
  
  - [ ] [prettyplotlib](https://github.com/olgabot/prettyplotlib)
  
# Web
  
### Framework
  - [ ] [wsgi](http://wsgi.readthedocs.io/en/latest/frameworks.html）
  
  - [ ] [webpy](https://github.com/webpy/webpy)
      
        "Django lets you write web apps in Django. TurboGears lets you write web apps in TurboGears. Web.py lets you write web apps in Python."
          —  Adam Atlas
          
        $ pip install web.py
        
        import web
        urls = ( '/(.*)', 'hello')
        app = web.application(urls, globals())
        class hello:  
          def GET(self, name):
            if not name: 
              name = 'World'
            return 'Hello, ' + name + '!'
        if __name__ == "__main__":
          app.run()
          
  - [ ] [falcon](https://github.com/falconry/falcon)
    
  - [ ] [aiohttp:Client/Server](https://github.com/aio-libs/aiohttp)
  
  ### Django-Case
  
  - [ ] [NewsBlur:Read-News-From-Variable-Sources](https://github.com/samuelclay/NewsBlur)
  
  - [ ] [django-imagekit](https://github.com/matthewwithanm/django-imagekit)
 
  ### Flask-Case
  
  - [ ] [Flask-AppBuilder](https://github.com/dpgaspar/Flask-AppBuilder)
  
  ### Utility
  
  - [ ] [password-strength-check](https://github.com/SirCmpwn/evilpass)
  
  - [ ] [qrcode](https://github.com/lincolnloop/python-qrcode)
  
# Machine Learning

### DataSet
        
   - [ ] [skdata](https://github.com/jaberg/skdata/tree/master/skdata)

### Overview

   - [ ] [off99555](https://github.com/off99555/machine-learning-curriculum)
   
### NLP

  - [ ] [spacy](https://spacy.io/) : [src](https://github.com/explosion/spaCy) : [models](https://github.com/explosion/spacy-models/)
  
        import spacy
        nlp = spacy.load('en')
        doc1 = nlp(u'the fries were gross')
        doc2 = nlp(u'worst fries ever')
        doc1.similarity(doc2)
        
  - [x] [gensim](https://github.com/RaRe-Technologies/gensim)
  
       * [tutorials](https://github.com/RaRe-Technologies/gensim/blob/develop/tutorials.md)
       * [doc2vec](https://github.com/RaRe-Technologies/gensim/blob/develop/docs/notebooks/doc2vec-lee.ipynb)
       * [summarization](https://github.com/RaRe-Technologies/gensim/blob/develop/docs/notebooks/summarization_tutorial.ipynb)
       
  - [ ] [newspaper:request+lxml+nltk+jieba](https://github.com/codelucas/newspaper)

        py3$ pip install newspaper3k
        py2$ pip install newspaper
        from newspaper import Article
        url = 'http://fox13now.com/2013/12/30/new-year-new-laws-obamacare-pot-guns-and-drones/'
        article = Article(url)
        article.download()
        article.parse()
        article.authors
        article.publish_date
        article.text
        article.top_image
        article.movies
        article.nlp()
        article.keywords
        article.summary
        from newspaper import fulltext
        html = requests.get(...).text
        text = fulltext(html)
        
  - [ ] [TextBlob](https://github.com/sloria/TextBlob)
  
  - [ ] [translate.py](https://bitbucket.org/frank0125/biddingdocument/src/8f034d22a750c5e08b593d79df7808fcf1f030f9/processing/trans.py?at=master&fileviewer=file-view-default)
  
  - [ ] [summarize](https://github.com/miso-belica/sumy)

  ### Prediction
  
  - [ ] [prophet](https://github.com/facebook/prophet) : [Quick-Start](https://facebook.github.io/prophet/docs/quick_start.html#python-api)
  
        import pandas as pd
        import numpy as np
        from fbprophet import Prophet
        df = pd.read_csv('../examples/example_wp_peyton_manning.csv')
        df['y'] = np.log(df['y'])
        df.head()
        m = Prophet()
        m.fit(df)
        
  ### Recommendation
   
   - [ ] [crab](https://github.com/muricoca/crab)
   
        
# Computer Vision
### Super Resolution
  - [ ] [srez:super-resolution-16x16to64x64-face](https://github.com/david-gpu/srez)
  
  - [ ] [neural-enhance](https://github.com/alexjc/neural-enhance)

# Office
### Excel
  
  - [ ] [xlrd](https://github.com/python-excel/xlrd)
  
  - [ ] [XlsxWriter](https://github.com/jmcnamara/XlsxWriter)
