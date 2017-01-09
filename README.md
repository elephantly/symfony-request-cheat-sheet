# symfony-request-cheat-sheet
A Cheat Sheet to know what you can find in your Request Object


object(Symfony\Component\HttpFoundation\Request)#4 (21) {
  ["attributes"]=>
  object(Symfony\Component\HttpFoundation\ParameterBag)#7 (1) {
    ["parameters":protected]=>
    array(6) {
      ["id"]=>
      string(5) "11832"
      ["provider"]=>
      NULL
      ["verb"]=>
      string(4) "view"
      ["_controller"]=>
      string(51) "Project\AppBundle\Controller\AppController::crudAction"
      ["_route"]=>
      string(13) "project_crud"
      ["_route_params"]=>
      array(3) {
        ["id"]=>
        string(5) "11832"
        ["provider"]=>
        NULL
        ["verb"]=>
        string(4) "view"
      }
    }
  }
  ["request"]=>
  object(Symfony\Component\HttpFoundation\ParameterBag)#5 (1) {
    ["parameters":protected]=>
    array(0) {
    }
  }
  ["query"]=>
  object(Symfony\Component\HttpFoundation\ParameterBag)#6 (1) {
    ["parameters":protected]=>
    array(0) {
    }
  }
  ["server"]=>
  object(Symfony\Component\HttpFoundation\ServerBag)#10 (1) {
    ["parameters":protected]=>
    array(34) {
      ["USER"]=>
      string(8) "www-data"
      ["HOME"]=>
      string(8) "/var/www"
      ["FCGI_ROLE"]=>
      string(9) "RESPONDER"
      ["QUERY_STRING"]=>
      string(0) ""
      ["REQUEST_METHOD"]=>
      string(3) "GET"
      ["CONTENT_TYPE"]=>
      string(0) ""
      ["CONTENT_LENGTH"]=>
      string(0) ""
      ["SCRIPT_NAME"]=>
      string(8) "/app.php"
      ["REQUEST_URI"]=>
      string(17) "/video/view/11832"
      ["DOCUMENT_URI"]=>
      string(8) "/app.php"
      ["DOCUMENT_ROOT"]=>
      string(23) "/data/www/project/web"
      ["SERVER_PROTOCOL"]=>
      string(8) "HTTP/1.1"
      ["REQUEST_SCHEME"]=>
      string(4) "http"
      ["GATEWAY_INTERFACE"]=>
      string(7) "CGI/1.1"
      ["SERVER_SOFTWARE"]=>
      string(12) "nginx/1.11.5"
      ["REMOTE_ADDR"]=>
      string(12) "0.0.0.0"
      ["REMOTE_PORT"]=>
      string(5) "51862"
      ["SERVER_ADDR"]=>
      string(10) "0.0.0.0"
      ["SERVER_PORT"]=>
      string(2) "80"
      ["SERVER_NAME"]=>
      string(23) "project.website.fr"
      ["REDIRECT_STATUS"]=>
      string(3) "200"
      ["SCRIPT_FILENAME"]=>
      string(31) "/data/www/project/web/app.php"
      ["HTTP_HOST"]=>
      string(29) "local.project.website.fr"
      ["HTTP_CONNECTION"]=>
      string(10) "keep-alive"
      ["HTTP_UPGRADE_INSECURE_REQUESTS"]=>
      string(1) "1"
      ["HTTP_USER_AGENT"]=>
      string(105) "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/54.0.2840.100 Safari/537.36"
      ["HTTP_ACCEPT"]=>
      string(74) "text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8"
      ["HTTP_REFERER"]=>
      string(43) "http://local.project.website.fr/search"
      ["HTTP_ACCEPT_ENCODING"]=>
      string(19) "gzip, deflate, sdch"
      ["HTTP_ACCEPT_LANGUAGE"]=>
      string(35) "fr-FR,fr;q=0.8,en-US;q=0.6,en;q=0.4"
      ["HTTP_COOKIE"]=>
      string(578) "xtvrn=$40086$; __qca=P0-341828280-1466086015817; __gads=ID=6b5250c7f3023f88:T=1466516395:S=ALNI_MalUux85njyeSliujDVYJqsy2UOzg; xtan40086=-; xtant40086=1; PHPSESSID=1ecqomi4t930n7g92l8vkgb3l3; _ga=GA1.2.896930901.1465570339; ABTasty=LPT103038%3A145150.1465911194%5E%7C%5ELPT140751%3A195918.1476352886%5E%7C%5ELPT149627%3A0.1479725756%5E%7C%5EABTastyUTMB%3A1%5E%7C%5ELPT149628%3A-2.1479990900%5E%7C%5ELiwioTracking%3A16061016521945532*149627.0%5E%7C%5EsegmentationTracking%3A16061016521945532%5E%7C%5ELiwioUTMA%3A0.43.1465570339006.1480424829613.1480600789891.1*103038.41*149627.5"
      ["PHP_SELF"]=>
      string(8) "/app.php"
      ["REQUEST_TIME_FLOAT"]=>
      float(1481277117.704)
      ["REQUEST_TIME"]=>
      int(1481277117)
    }
  }
  ["files"]=>
  object(Symfony\Component\HttpFoundation\FileBag)#9 (1) {
    ["parameters":protected]=>
    array(0) {
    }
  }
  ["cookies"]=>
  object(Symfony\Component\HttpFoundation\ParameterBag)#8 (1) {
    ["parameters":protected]=>
    array(8) {
      ["xtvrn"]=>
      string(7) "$xxxxx$"
      ["__qca"]=>
      string(26) "P0-xxxxxxxxxxx-xxxxxxxxxxxxx"
      ["__gads"]=>
      string(69) "ID=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
      ["xtan40086"]=>
      string(1) "-"
      ["xtant40086"]=>
      string(1) "1"
      ["PHPSESSID"]=>
      string(26) "xxxxxxxxxxxxxxxxxxxxxxx"
      ["_ga"]=>
      string(26) "GA1.x.xxxxxxxx.xxxxxxxxx"
      ["ABTasty"]=>
      string(288) "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
    }
  }
  ["headers"]=>
  object(Symfony\Component\HttpFoundation\HeaderBag)#11 (2) {
    ["headers":protected]=>
    array(12) {
      ["content-type"]=>
      array(1) {
        [0]=>
        string(0) ""
      }
      ["content-length"]=>
      array(1) {
        [0]=>
        string(0) ""
      }
      ["host"]=>
      array(1) {
        [0]=>
        string(29) "local.project.website.fr"
      }
      ["connection"]=>
      array(1) {
        [0]=>
        string(10) "keep-alive"
      }
      ["upgrade-insecure-requests"]=>
      array(1) {
        [0]=>
        string(1) "1"
      }
      ["user-agent"]=>
      array(1) {
        [0]=>
        string(105) "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/54.0.2840.100 Safari/537.36"
      }
      ["accept"]=>
      array(1) {
        [0]=>
        string(74) "text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8"
      }
      ["referer"]=>
      array(1) {
        [0]=>
        string(43) "http://local.project.website.fr/search"
      }
      ["accept-encoding"]=>
      array(1) {
        [0]=>
        string(19) "gzip, deflate, sdch"
      }
      ["accept-language"]=>
      array(1) {
        [0]=>
        string(35) "fr-FR,fr;q=0.8,en-US;q=0.6,en;q=0.4"
      }
      ["cookie"]=>
      array(1) {
        [0]=>
        string(578) "xtvrn=$xxxxxx$; __qca=P0-xxxxxxxxxxx-xxxxxxxxxxxxx; __gads=ID=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx; xtanxxxxxx=-; xtantxxxxxx=1; PHPSESSID=xxxxxxxxxxxxxxxxxxxxxxx; _ga=GA1.x.xxxxxxxx.xxxxxxxxx; ABTasty=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
      }
      ["x-php-ob-level"]=>
      array(1) {
        [0]=>
        int(1)
      }
    }
    ["cacheControl":protected]=>
    array(0) {
    }
  }
  ["content":protected]=>
  NULL
  ["languages":protected]=>
  NULL
  ["charsets":protected]=>
  NULL
  ["encodings":protected]=>
  NULL
  ["acceptableContentTypes":protected]=>
  NULL
  ["pathInfo":protected]=>
  string(17) "/video/view/11832"
  ["requestUri":protected]=>
  string(17) "/video/view/11832"
  ["baseUrl":protected]=>
  string(0) ""
  ["basePath":protected]=>
  NULL
  ["method":protected]=>
  string(3) "GET"
  ["format":protected]=>
  NULL
  ["session":protected]=>
  object(Symfony\Component\HttpFoundation\Session\Session)#56 (3) {
    ["storage":protected]=>
    object(Symfony\Component\HttpFoundation\Session\Storage\NativeSessionStorage)#57 (5) {
      ["bags":protected]=>
      array(2) {
        ["attributes"]=>
        object(Symfony\Component\HttpFoundation\Session\Attribute\AttributeBag)#61 (3) {
          ["name":"Symfony\Component\HttpFoundation\Session\Attribute\AttributeBag":private]=>
          string(10) "attributes"
          ["storageKey":"Symfony\Component\HttpFoundation\Session\Attribute\AttributeBag":private]=>
          string(15) "_sf2_attributes"
          ["attributes":protected]=>
          &array(4) {
            ["_security.main.target_path"]=>
            string(37) "http://local.project.website.fr/"
            ["_csrf/login"]=>
            string(43) "gTvwcHKfvcnwFLvULNXMLXHKw6c2jgRsPpz5p63ooak"
            ["_security_main"]=>
            string(2579) "C:67:"Symfony\Component\Security\Guard\Token\PostAuthenticationGuardToken":2497:{a:2:{i:0;s:4:"main";i:1;s:2462:"a:4:{i:0;O:26:"Project\AppBundle\Entity\User":10:{s:5:"*id";i:3;s:12:"*firstname";s:5:"admin";s:11:"*lastname";s:5:"admin";s:12:"*usergroup";O:31:"Project\AppBundle\Entity\Usergroup":5:{s:35:"Project\AppBundle\Entity\Usergroupid";i:5;s:42:"Project\AppBundle\Entity\UsergroupgroupName";s:6:"admins";s:44:"Project\AppBundle\Entity\Usergroupdescription";s:11:"Site admins";s:37:"Project\AppBundle\Entity\Usergrouprole";s:10:"ROLE_ADMIN";s:8:"*array";a:0:{}}s:11:"*username";s:5:"admin";s:11:"*password";s:13:"xxxxxxxxx";s:8:"*email";s:17:"admin@example.com";s:8:"*roles";a:1:{i:0;s:10:"ROLE_ADMIN";}s:8:"*token";s:796:"XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX";}}i:1;b:1;i:2;a:1:{i:0;O:41:"Symfony\Component\Security\Core\Role\Role":1:{s:47:"Symfony\Component\Security\Core\Role\Rolerole";s:10:"ROLE_ADMIN";}}i:3;a:0:{}}";}}"
            ["_csrf/video_search"]=>
            string(43) "BZ4ynsy9pIHD9dnk_8KO9ks_tmhs1DgL0ZU2x4zPkVw"
          }
        }
        ["flashes"]=>
        object(Symfony\Component\HttpFoundation\Session\Flash\FlashBag)#62 (3) {
          ["name":"Symfony\Component\HttpFoundation\Session\Flash\FlashBag":private]=>
          string(7) "flashes"
          ["flashes":"Symfony\Component\HttpFoundation\Session\Flash\FlashBag":private]=>
          &array(0) {
          }
          ["storageKey":"Symfony\Component\HttpFoundation\Session\Flash\FlashBag":private]=>
          string(12) "_sf2_flashes"
        }
      }
      ["started":protected]=>
      bool(true)
      ["closed":protected]=>
      bool(false)
      ["saveHandler":protected]=>
      object(Symfony\Component\HttpFoundation\Session\Storage\Proxy\SessionHandlerProxy)#59 (4) {
        ["handler":protected]=>
        object(SessionHandler)#60 (0) {
        }
        ["wrapper":protected]=>
        bool(true)
        ["active":protected]=>
        bool(true)
        ["saveHandlerName":protected]=>
        string(5) "files"
      }
      ["metadataBag":protected]=>
      object(Symfony\Component\HttpFoundation\Session\Storage\MetadataBag)#58 (5) {
        ["name":"Symfony\Component\HttpFoundation\Session\Storage\MetadataBag":private]=>
        string(10) "__metadata"
        ["storageKey":"Symfony\Component\HttpFoundation\Session\Storage\MetadataBag":private]=>
        string(9) "_sf2_meta"
        ["meta":protected]=>
        &array(3) {
          ["u"]=>
          int(1481277117)
          ["c"]=>
          int(1481276983)
          ["l"]=>
          string(1) "0"
        }
        ["lastUsed":"Symfony\Component\HttpFoundation\Session\Storage\MetadataBag":private]=>
        int(1481277060)
        ["updateThreshold":"Symfony\Component\HttpFoundation\Session\Storage\MetadataBag":private]=>
        string(1) "0"
      }
    }
    ["flashName":"Symfony\Component\HttpFoundation\Session\Session":private]=>
    string(7) "flashes"
    ["attributeName":"Symfony\Component\HttpFoundation\Session\Session":private]=>
    string(10) "attributes"
  }
  ["locale":protected]=>
  NULL
  ["defaultLocale":protected]=>
  string(2) "fr"
}
