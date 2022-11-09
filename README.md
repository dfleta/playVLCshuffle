# VLC Play Shuffle

Chequea si tu libreria dispone de los módulos estándar `os, subprocess` y el _framework_ `shlex` :

 - os
 - subprocess
 - shlex

```sh
$ python3.10
>>> help("modules")

Please wait a moment while I gather a list of all available modules...

__future__          _testinternalcapi   getpass             runpy
_abc                _testmultiphase     gettext             sched
_aix_support        _thread             glob                secrets
_ast                _threading_local    graphlib            select
_asyncio            _tkinter            grp                 selectors
_bisect             _tracemalloc        gzip                setuptools
_blake2             _uuid               hashlib             shelve
_bootsubprocess     _warnings           heapq               shlex       !!!!!!!!!!
_bz2                _weakref            hmac                shutil
_codecs             _weakrefset         html                signal
_codecs_cn          _xxsubinterpreters  http                site
_codecs_hk          _xxtestfuzz         imaplib             sitecustomize
_codecs_iso2022     _zoneinfo           imghdr              smtpd
_codecs_jp          abc                 imp                 smtplib
_codecs_kr          accesoDatosOCP      importlib           sndhdr
_codecs_tw          aifc                inspect             socket
_collections        antigravity         io                  socketserver
_collections_abc    argparse            ipaddress           spwd
_compat_pickle      array               itertools           sqlite3
_compression        ast                 json                sre_compile
_contextvars        asynchat            keyword             sre_constants
_crypt              asyncio             lib2to3             sre_parse
_csv                asyncore            linecache           ssl
_ctypes             atexit              locale              stat
_ctypes_test        audioop             logging             statistics
_curses             base64              lzma                string
_curses_panel       bdb                 mailbox             stringprep
_datetime           binascii            mailcap             struct
_dbm                binhex              marshal             subprocess    !!!!!!!!
_decimal            bisect              math                sunau
_distutils_hack     builtins            mimetypes           symtable
_distutils_system_mod bz2                 mmap                sys
_elementtree        cProfile            modulefinder        sysconfig
_functools          calendar            multiprocessing     syslog
_gdbm               cgi                 netrc               tabnanny
_hashlib            cgitb               nis                 tarfile
_heapq              chunk               nntplib             telnetlib
_imp                cmath               ntpath              tempfile
_io                 cmd                 nturl2path          termios
_json               code                numbers             test
_locale             codecs              opcode              textwrap
_lsprof             codeop              operator            this
_lzma               collections         optparse            threading
_markupbase         colorsys            os     !!!!!!             time
_md5                compileall          ossaudiodev         timeit
_multibytecodec     concurrent          pathlib             tkinter
_multiprocessing    configparser        pdb                 token
_opcode             contextlib          pickle              tokenize
_operator           contextvars         pickletools         trace
_osx_support        copy                pip                 traceback
_pickle             copyreg             pipes               tracemalloc
_posixshmem         crypt               pkg_resources       tty
_posixsubprocess    csv                 pkgutil             turtle
_py_abc             ctypes              platform            types
_pydecimal          curses              playShuffleVLC      typing
_pyio               dataclasses         playShuffleVLC_DAO  unicodedata
_queue              datetime            playShuffleVLC_comentado unittest
_random             dbm                 plistlib            urllib
_sha1               decimal             poplib              uu
_sha256             difflib             posix               uuid
_sha3               dis                 posixpath           venv
_sha512             distutils           pprint              warnings
_signal             doctest             profile             wave
_sitebuiltins       email               pstats              weakref
_socket             encodings           pty                 webbrowser
_sqlite3            ensurepip           pwd                 wsgiref
_sre                enum                py_compile          xdrlib
_ssl                errno               pyclbr              xml
_stat               faulthandler        pydoc               xmlrpc
_statistics         fcntl               pydoc_data          xxlimited
_string             filecmp             pyexpat             xxlimited_35
_strptime           fileinput           queue               xxsubtype
_struct             fnmatch             quopri              zipapp
_symtable           fractions           random              zipfile
_sysconfigdata__linux_x86_64-linux-gnu ftplib              re                  zipimport
_sysconfigdata__x86_64-linux-gnu functools           readline            zlib
_testbuffer         gc                  reprlib             zoneinfo
_testcapi           genericpath         resource            
_testimportmultiple getopt              rlcompleter         
```