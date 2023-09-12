## Curl options used:
|     Options      | Description                                                                                                                |
|:----------------:|:-------------------------------------------------------------------------------------------------------------------------- |
|  -4 ``--ipv4``   | This option tells curl to use IPv4 addresses only when resolving host names, and not for example try IPv6.                 |
| -v ``--verbose`` | Makes curl verbose during the operation. Useful for debugging and seeing what's going on "under the hood".                 |
|  -I ``--head``   | Fetch the headers only! HTTP-servers feature the command HEAD which this uses to get nothing but the header of a document. |
___
## Site: [RGUPS](https://www.rgups.ru)
#### Results for: rgups.ru
> __Use:__
> ```shell
> curl -4vI rgups.ru
>```
>__Result:__
>```shell
>  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                 Dload  Upload   Total   Spent    Left  Speed
> 0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 80.72.224.90:80...
> * Connected to rgups.ru (80.72.224.90) port 80 (#0)
> 0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0> HEAD / HTTP/1.1
> Host: rgups.ru
> User-Agent: curl/7.87.0
> Accept: */*
> * Mark bundle as not supporting multiuse
> < HTTP/1.1 301 Moved Permanently
> < Server: nginx/1.19.1
> < Date: Tue, 12 Sep 2023 17:34:53 GMT
> < Content-Type: text/html
> < Content-Length: 169
> < Connection: keep-alive
> < Location: https://rgups.ru/
> <
> 0   169    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/1.1 301 Moved Permanently
> Server: nginx/1.19.1
> Date: Tue, 12 Sep 2023 17:34:53 GMT
> Content-Type: text/html
> Content-Length: 169
> Connection: keep-alive
> Location: https://rgups.ru/
>```
>
>  __Info:__
> - Ip: ``80.72.224.90``
> - Port: ``80``
> - Host: ``rgups.ru``
> - Cache-Control: ``-``
> - Content-Type: ``text/html``
> - Response code: ``301 - the page has been permanently moved to a different address``
> - Protocol: ``HTTP/1.1``

#### Results for: www.rgups.ru
> __Use:__
> ```shell
> curl -4vI www.rgups.ru
>```
>__Result:__
>```shell
>  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                  Dload  Upload   Total   Spent    Left  Speed
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 80.72.224.90:80...
> * Connected to www.rgups.ru (80.72.224.90) port 80 (#0)
> HEAD / HTTP/1.1
> Host: www.rgups.ru
> User-Agent: curl/7.87.0
> Accept: */*
> * Mark bundle as not supporting multiuse
> < HTTP/1.1 301 Moved Permanently
> < Server: nginx/1.19.1
> < Date: Tue, 12 Sep 2023 18:21:40 GMT
> < Content-Type: text/html
> < Content-Length: 169
> < Connection: keep-alive
> < Location: https://www.rgups.ru/
> <
>  0   169    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/1.1 301 Moved Permanently
> Server: nginx/1.19.1
> Date: Tue, 12 Sep 2023 18:21:40 GMT
> Content-Type: text/html
> Content-Length: 169
> Connection: keep-alive
> Location: https://www.rgups.ru/
>```
>
>  __Info:__
> - Ip: ``80.72.224.90``
> - Port: ``80``
> - Host: ``www.rgups.ru``
> - Cache-Control: ``-``
> - Content-Type: ``text/html``
> - Response code: ``301 - the page has been permanently moved to a different address``
> - Protocol: ``HTTP/1.1``

#### Results for: http://rgups.ru
> __Use:__
> ```shell
> curl -4vI http://rgups.ru
>```
>__Result:__
>```shell
>    % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                  Dload  Upload   Total   Spent    Left  Speed
>  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 80.72.224.90:80...
> * Connected to rgups.ru (80.72.224.90) port 80 (#0)
> HEAD / HTTP/1.1
> Host: rgups.ru
> User-Agent: curl/7.87.0
> Accept: */*
>
> * Mark bundle as not supporting multiuse
> < HTTP/1.1 301 Moved Permanently
> < Server: nginx/1.19.1
> < Date: Tue, 12 Sep 2023 18:26:13 GMT
> < Content-Type: text/html
> < Content-Length: 169
> < Connection: keep-alive
> < Location: https://rgups.ru/
> <
>  0   169    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/1.1 301 Moved Permanently
> Server: nginx/1.19.1
> Date: Tue, 12 Sep 2023 18:26:13 GMT
> Content-Type: text/html
> Content-Length: 169
> Connection: keep-alive
> Location: https://rgups.ru/
>```
>
>  __Info:__
> - Ip: ``80.72.224.90``
> - Port: ``80``
> - Host: ``rgups.ru``
> - Cache-Control: ``-``
> - Content-Type: ``text/html``
> - Response code: ``301 - the page has been permanently moved to a different address``
> - Protocol: ``HTTP/1.1``

#### Results for: https://rgups.ru
> __Use:__
> ```shell
> curl -4vI https://rgups.ru
>```
>__Result:__
>```shell
>   % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                  Dload  Upload   Total   Spent    Left  Speed
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 80.72.224.90:443...
> * Connected to rgups.ru (80.72.224.90) port 443 (#0)
> * ALPN: offers h2
> * ALPN: offers http/1.1
> *  CAfile: C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
> *  CApath: none
> } [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Client hello (1):
> } [512 bytes data]
>  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0* [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Server hello (2):
> { [112 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Certificate (11):
> { [3980 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Server key exchange (12):
> { [300 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Server finished (14):
> { [4 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (OUT), TLS handshake, Client key exchange (16):
> } [37 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (OUT), TLS change cipher, Change cipher spec (1):
> } [1 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (OUT), TLS handshake, Finished (20):
> } [16 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Finished (20):
> { [16 bytes data]
> * SSL connection using TLSv1.2 / ECDHE-RSA-CHACHA20-POLY1305
> * ALPN: server accepted http/1.1
> * Server certificate:
> *  subject: CN=rgups.ru
> *  start date: Jul 26 05:05:48 2023 GMT
> *  expire date: Oct 24 05:05:47 2023 GMT
> *  subjectAltName: host "rgups.ru" matched cert's "rgups.ru"
> *  issuer: C=US; O=Let's Encrypt; CN=R3
> *  SSL certificate verify ok.
> } [5 bytes data]
> > HEAD / HTTP/1.1
> > Host: rgups.ru
> > User-Agent: curl/7.87.0
> > Accept: */*
> >
> { [5 bytes data]
> * Mark bundle as not supporting multiuse
> < HTTP/1.1 200 OK
> < Server: nginx/1.19.1
> < Date: Tue, 12 Sep 2023 18:33:39 GMT
> < Content-Type: text/html; charset=utf-8
> < Connection: keep-alive
> < X-Powered-By: ProcessWire CMS
> < Set-Cookie: wire=92eb111ea5f181104gg4a818e1e4171a; path=/; HttpOnly; SameSite=Lax
> < Expires: Thu, 19 Nov 1981 08:52:00 GMT
> < Cache-Control: no-store, no-cache, must-revalidate
> < Pragma: no-cache
> <
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/1.1 200 OK
> Server: nginx/1.19.1
> Date: Tue, 12 Sep 2023 18:33:39 GMT
> Content-Type: text/html; charset=utf-8
> Connection: keep-alive
> X-Powered-By: ProcessWire CMS
> Set-Cookie: wire=92eb111ea5f181104gg4a818e1e4171a; path=/; HttpOnly; SameSite=Lax
> Expires: Thu, 19 Nov 1981 08:52:00 GMT
> Cache-Control: no-store, no-cache, must-revalidate
> Pragma: no-cache
>```
>
>  __Info:__
> - Ip: ``80.72.224.90``
> - Port: ``443``
> - Host: ``rgups.ru``
> - Cache-Control: ``no-store, no-cache, must-revalidate``
> - Content-Type: ``text/html; charset=utf-8``
> - Response code: ``200 - OK. The client's request was completed successfully.``
> - Protocol: ``HTTP/1.1``
> - Use SSL: ``TLSv1.2``

## Site: [Github](https://github.com/)
#### Results for: https://github.com/
> __Use:__
> ```shell
> curl -4vI https://github.com/
>```
>__Result:__
>```shell
>  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                  Dload  Upload   Total   Spent    Left  Speed
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 140.82.121.4:443...
> * Connected to github.com (140.82.121.4) port 443 (#0)
> * ALPN: offers h2
> * ALPN: offers http/1.1
> *  CAfile: C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
> *  CApath: none
> } [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Client hello (1):
> } [512 bytes data]
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0* [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Server hello (2):
> { [122 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Encrypted Extensions (8):
> { [19 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Certificate (11):
> { [2459 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, CERT verify (15):
> { [80 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Finished (20):
> { [36 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS change cipher, Change cipher spec (1):
> } [1 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Finished (20):
> } [36 bytes data]
> * SSL connection using TLSv1.3 / TLS_AES_128_GCM_SHA256
> * ALPN: server accepted h2
> * Server certificate:
> *  subject: C=US; ST=California; L=San Francisco; O=GitHub, Inc.; CN=github.com
> *  start date: Feb 14 00:00:00 2023 GMT
> *  expire date: Mar 14 23:59:59 2024 GMT
> *  subjectAltName: host "github.com" matched cert's "github.com"
> *  issuer: C=US; O=DigiCert Inc; CN=DigiCert TLS Hybrid ECC SHA384 2020 CA1
> *  SSL certificate verify ok.
> * Using HTTP2, server supports multiplexing
> * Copying HTTP/2 data in stream buffer to connection buffer after upgrade: len=0
> } [5 bytes data]
> * h2h3 [:method: HEAD]
> * h2h3 [:path: /]
> * h2h3 [:scheme: https]
> * h2h3 [:authority: github.com]
> * h2h3 [user-agent: curl/7.87.0]
> * h2h3 [accept: */*]
> * Using Stream ID: 1 (easy handle 0x1f630ce1fa0)
> } [5 bytes data]
> > HEAD / HTTP/2
> > Host: github.com
> > user-agent: curl/7.87.0
> > accept: */*
> >
> { [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Newsession Ticket (4):
> { [57 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Newsession Ticket (4):
> { [57 bytes data]
> * old SSL session ID is stale, removing
> { [5 bytes data]
> < HTTP/2 200
> < server: GitHub.com
> < date: Tue, 12 Sep 2023 19:03:35 GMT
> < content-type: text/html; charset=utf-8
> < vary: X-PJAX, X-PJAX-Container, Turbo-Visit, Turbo-Frame, Accept-Language, Accept-Encoding, Accept, X-Requested-With
> < content-language: en-US
> < etag: W/"90247860d2342358996e23231215c4"
> < cache-control: max-age=0, private, must-revalidate
> < strict-transport-security: max-age=31536000; includeSubdomains; preload
> < x-frame-options: deny
> < x-content-type-options: nosniff
> < x-xss-protection: 0
> < referrer-policy: origin-when-cross-origin, strict-origin-when-cross-origin
> < content-security-policy: default-src 'none'; base-uri 'self'; child-src github.com/assets-cdn/worker/ gist.github.com/assets-cdn/worker/; connect-src 'self' uploads.github.com objects-origin.githubusercontent.com www.githubstatus.com collector.github.com raw.githubusercontent.com api.github.com github-cloud.s3.amazonaws.com github-production-repository-file-5c1aeb.s3.amazonaws.com github-production-upload-manifest-file-7fdce7.s3.amazonaws.com github-production-user-asset-6210df.s3.amazonaws.com cdn.optimizely.com logx.optimizely.com/v1/events *.actions.githubusercontent.com productionresultssa0.blob.core.windows.net/ productionresultssa1.blob.core.windows.net/ productionresultssa2.blob.core.windows.net/ productionresultssa3.blob.core.windows.net/ productionresultssa4.blob.core.windows.net/ productionresultssa5.blob.core.windows.net/ productionresultssa6.blob.core.windows.net/ productionresultssa7.blob.core.windows.net/ productionresultssa8.blob.core.windows.net/ productionresultssa9.blob.core.windows.net/ wss://*.actions.githubusercontent.com github-production-repository-image-32fea6.s3.amazonaws.com github-production-release-asset-2e65be.s3.amazonaws.com insights.github.com wss://alive.github.com github.githubassets.com; font-src github.githubassets.com; form-action 'self' github.com gist.github.com objects-origin.githubusercontent.com; frame-ancestors 'none'; frame-src viewscreen.githubusercontent.com notebooks.githubusercontent.com support.github.com; img-src 'self' data: github.githubassets.com media.githubusercontent.com camo.githubusercontent.com identicons.github.com avatars.githubusercontent.com github-cloud.s3.amazonaws.com objects.githubusercontent.com objects-origin.githubusercontent.com secured-user-images.githubusercontent.com/ user-images.githubusercontent.com/ private-user-images.githubusercontent.com opengraph.githubassets.com github-production-user-asset-6210df.s3.amazonaws.com customer-stories-feed.github.com spotlights-feed.github.com *.githubusercontent.com; manifest-src 'self'; media-src github.com user-images.githubusercontent.com/ secured-user-images.githubusercontent.com/ private-user-images.githubusercontent.com github.githubassets.com; script-src github.githubassets.com; style-src 'unsafe-inline' github.githubassets.com; upgrade-insecure-requests; worker-src github.com/assets-cdn/worker/ gist.github.com/assets-cdn/worker/
> < set-cookie: _gh_sess=cvs5niY223anhp6t%2Fi6a28H5wZRgU6qDFjwNN7v4uMm87YLXNbXARiuGC%2BOCSYIQqNajnj549SFNXPgxCeQ534534rte%2FQ3%2FuC288orWRiEhvMZKvxiuDlXO%2Bcl0QUMGHM6MVKJrQR9TdlFsYDZmeirb9y9Mwe8e6zjCEq1x2UHikowobPDiDTmZbfW92GxAIv5WT9XUqpPcaqgYocE345345AEOptn%2BWylIw7MZoh9%2Fq123123qXOjd6r47cfFWM6aNReUBJ3VQ2rrZIQ%3D%3asddasdiZR%2BT2vfIqJ--3mrwqYLBDH6ZXL4znawvAQ%3D%3D; Path=/; HttpOnly; Secure; SameSite=Lax
> < set-cookie: _octo=GH1.1.545388337.1694545417; Path=/; Domain=github.com; Expires=Thu, 12 Sep 2024 19:03:37 GMT; Secure; SameSite=Lax
> < set-cookie: logged_in=no; Path=/; Domain=github.com; Expires=Thu, 12 Sep 2024 19:03:37 GMT; HttpOnly; Secure; SameSite=Lax
> < accept-ranges: bytes
> < x-github-request-id: 1366:7C92:7022B39:719AD82:6500B609
> <
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/2 200
> server: GitHub.com
> date: Tue, 12 Sep 2023 19:03:35 GMT
> content-type: text/html; charset=utf-8
> vary: X-PJAX, X-PJAX-Container, Turbo-Visit, Turbo-Frame, Accept-Language, Accept-Encoding, Accept, X-Requested-With
> content-language: en-US
> etag: W/"90247860d5d3ff818996e801e21215c4"
> cache-control: max-age=0, private, must-revalidate
> strict-transport-security: max-age=31536000; includeSubdomains; preload
> x-frame-options: deny
> x-content-type-options: nosniff
> x-xss-protection: 0
> referrer-policy: origin-when-cross-origin, strict-origin-when-cross-origin
> content-security-policy: default-src 'none'; base-uri 'self'; child-src github.com/assets-cdn/worker/ gist.github.com/assets-cdn/worker/; connect-src 'self' uploads.github.com objects-origin.githubusercontent.com www.githubstatus.com collector.github.com raw.githubusercontent.com api.github.com github-cloud.s3.amazonaws.com github-production-repository-file-5c1aeb.s3.amazonaws.com github-production-upload-manifest-file-7fdce7.s3.amazonaws.com github-production-user-asset-6210df.s3.amazonaws.com cdn.optimizely.com logx.optimizely.com/v1/events *.actions.githubusercontent.com productionresultssa0.blob.core.windows.net/ productionresultssa1.blob.core.windows.net/ productionresultssa2.blob.core.windows.net/ productionresultssa3.blob.core.windows.net/ productionresultssa4.blob.core.windows.net/ productionresultssa5.blob.core.windows.net/ productionresultssa6.blob.core.windows.net/ productionresultssa7.blob.core.windows.net/ productionresultssa8.blob.core.windows.net/ productionresultssa9.blob.core.windows.net/ wss://*.actions.githubusercontent.com github-production-repository-image-32fea6.s3.amazonaws.com github-production-release-asset-2e65be.s3.amazonaws.com insights.github.com wss://alive.github.com github.githubassets.com; font-src github.githubassets.com; form-action 'self' github.com gist.github.com objects-origin.githubusercontent.com; frame-ancestors 'none'; frame-src viewscreen.githubusercontent.com notebooks.githubusercontent.com support.github.com; img-src 'self' data: github.githubassets.com media.githubusercontent.com camo.githubusercontent.com identicons.github.com avatars.githubusercontent.com github-cloud.s3.amazonaws.com objects.githubusercontent.com objects-origin.githubusercontent.com secured-user-images.githubusercontent.com/ user-images.githubusercontent.com/ private-user-images.githubusercontent.com opengraph.githubassets.com github-production-user-asset-6210df.s3.amazonaws.com customer-stories-feed.github.com spotlights-feed.github.com *.githubusercontent.com; manifest-src 'self'; media-src github.com user-images.githubusercontent.com/ secured-user-images.githubusercontent.com/ private-user-images.githubusercontent.com github.githubassets.com; script-src github.githubassets.com; style-src 'unsafe-inline' github.githubassets.com; upgrade-insecure-requests; worker-src github.com/assets-cdn/worker/ gist.github.com/assets-cdn/worker/
> set-cookie: _gh_sess=cvs5niY223anhp64534534345ZRgU6qDFjwNN7v4uMm87YLXNbXARiuGC%2BOCSYIQqNajnj549SFNXPgxCeQLO8pOxJ5aD%2FQ3%2FuC288orWRiEhvMZKvxiuDlXO%2Bcl0QUMGHM6MVKerterterter5462meiertetrterEq1x2UHikowobPDiDTmZbfW92GxAIv5WT9XUqpPcaqgYocEaH832trtrh67jeddddgdwwWylIw7MZoh9%2FqnnxqXOjd6r47cfFWM6aNReUBJ3VQ2rLki2CrZIQ%3D%3D--SI7SKiZR%2BT2vfIqJ--3mrwqYLBDH6ZXL4znawvAQ%3D%3D; Path=/; HttpOnly; Secure; SameSite=Lax
> set-cookie: _octo=GH1.1.345384237.1694145417; Path=/; Domain=github.com; Expires=Thu, 12 Sep 2024 19:03:37 GMT; Secure; SameSite=Lax
> set-cookie: logged_in=no; Path=/; Domain=github.com; Expires=Thu, 12 Sep 2024 19:03:37 GMT; HttpOnly; Secure; SameSite=Lax
> accept-ranges: bytes
> x-github-request-id: 1366:7C92:7011249:719A222:650022209
> 
>```
>
>  __Info:__
> - Ip: ``140.82.121.4``
> - Port: ``443``
> - Host: ``github.com``
> - Cache-Control: ``max-age=0, private, must-revalidate``
> - Content-Type: ``text/html; charset=utf-8``
> - Response code: ``200 - OK. The client's request was completed successfully.``
> - Protocol: ``HTTP/2``
> - Use SSL: ``TLSv1.3``

## Site: [RZD](https://www.rzd.ru/)
#### Results for: https://www.rzd.ru/
> __Use:__
> ```shell
> curl -4vI --User-agent "Google" https://www.rzd.ru/
>```
>__Result:__
>```shell
>  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                  Dload  Upload   Total   Spent    Left  Speed
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 212.164.138.128:443...
>   0     0    0     0    0     0      0      0 --:--:--  0:00:20 --:--:--     0* connect to 212.164.138.128 port 443 failed: Timed out
> *   Trying 212.164.138.126:443...
>   0     0    0     0    0     0      0      0 --:--:--  0:00:21 --:--:--     0* Connected to www.rzd.ru (212.164.138.126) port 443 (#0)
> * ALPN: offers h2
> * ALPN: offers http/1.1
> *  CAfile: C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
> *  CApath: none
> } [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Client hello (1):
> } [512 bytes data]
>   0     0    0     0    0     0      0      0 --:--:--  0:00:22 --:--:--     0* [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Server hello (2):
> { [112 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Certificate (11):
> { [3945 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Server key exchange (12):
> { [589 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Server finished (14):
> { [4 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (OUT), TLS handshake, Client key exchange (16):
> } [70 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (OUT), TLS change cipher, Change cipher spec (1):
> } [1 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (OUT), TLS handshake, Finished (20):
> } [16 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Finished (20):
> { [16 bytes data]
> * SSL connection using TLSv1.2 / ECDHE-RSA-AES256-GCM-SHA384
> * ALPN: server accepted http/1.1
> * Server certificate:
> *  subject: CN=*.rzd.ru
> *  start date: May 24 07:13:14 2023 GMT
> *  expire date: Jun 24 07:13:13 2024 GMT
> *  subjectAltName: host "www.rzd.ru" matched cert's "*.rzd.ru"
> *  issuer: C=BE; O=GlobalSign nv-sa; CN=GlobalSign GCC R3 DV TLS CA 2020
> *  SSL certificate verify ok.
> } [5 bytes data]
> > HEAD / HTTP/1.1
> > Host: www.rzd.ru
> > User-Agent: Google
> > Accept: */*
> >
> { [5 bytes data]
> * Mark bundle as not supporting multiuse
> < HTTP/1.1 200
> < Content-Type: text/html;charset=utf-8
> < Content-Length: 210101
> < Connection: keep-alive
> < Date: Tue, 12 Sep 2023 19:22:46 GMT
> < Vary: Accept-Encoding
> < X-UCM-Pod-Name: inex-ucm-716d97f9d-p87lc
> < Strict-Transport-Security: max-age=15724800; includeSubDomains
> < Via: nginx3
> < X-Frame-Options: sameorigin
> < Set-Cookie: session-cookie=17843d1f1212121212121212121212b105e7c1813046ac6344b6e1483096df6fb530e483da81de641f1b; Max-Age=86400; Path=/; secure; HttpOnly
> < X-XSS-Protection: 1; mode=block
> <
>   0  205k    0     0    0     0      0      0 --:--:--  0:00:22 --:--:--     0HTTP/1.1 200
> Content-Type: text/html;charset=utf-8
> Content-Length: 210101
> Connection: keep-alive
> Date: Tue, 12 Sep 2023 19:22:46 GMT
> Vary: Accept-Encoding
> X-UCM-Pod-Name: inex-ucm-776111f9d-p27lc
> Strict-Transport-Security: max-age=15724800; includeSubDomains
> Via: nginx3
> X-Frame-Options: sameorigin
> Set-Cookie: session-cookie=17843d1f1212121212121212121212b105e7c1813046ac6344b6e1483096df6fb530e483da81de641f1b; Max-Age=86400; Path=/; secure; HttpOnly
> X-XSS-Protection: 1; mode=block
>```
>
>  __Info:__
> - Ip: ``212.164.138.126``
> - Port: ``443``
> - Host: ``www.rzd.ru``
> - Cache-Control: ``-``
> - Content-Type: ``text/html;charset=utf-8``
> - Response code: ``200 - OK. The client's request was completed successfully.``
> - Protocol: ``HTTP/1.1``
> - Use SSL: ``TLSv1.2``

## Site: [yandex](https://yandex.ru/)
#### Results for: https://yandex.ru/
> __Use:__
> ```shell
> curl -4vI https://yandex.ru/
>```
>__Result:__
>```shell
>  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                  Dload  Upload   Total   Spent    Left  Speed
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 77.88.55.60:443...
> * Connected to yandex.ru (77.88.55.60) port 443 (#0)
> * ALPN: offers h2
> * ALPN: offers http/1.1
> *  CAfile: C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
> *  CApath: none
> } [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Client hello (1):
> } [512 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Server hello (2):
> { [122 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Encrypted Extensions (8):
> { [15 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Certificate (11):
> { [3672 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, CERT verify (15):
> { [79 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Finished (20):
> { [52 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS change cipher, Change cipher spec (1):
> } [1 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Finished (20):
> } [52 bytes data]
> * SSL connection using TLSv1.3 / TLS_AES_256_GCM_SHA384
> * ALPN: server accepted h2
> * Server certificate:
> *  subject: C=RU; ST=Moscow; L=Moscow; O=Yandex LLC; CN=*.xn--d1acpjx3f.xn--p1ai
> *  start date: Jun 21 13:42:48 2023 GMT
> *  expire date: Dec 19 20:59:59 2023 GMT
> *  subjectAltName: host "yandex.ru" matched cert's "yandex.ru"
> *  issuer: C=BE; O=GlobalSign nv-sa; CN=GlobalSign ECC OV SSL CA 2018
> *  SSL certificate verify ok.
> * Using HTTP2, server supports multiplexing
> * Copying HTTP/2 data in stream buffer to connection buffer after upgrade: len=0
> } [5 bytes data]
> * h2h3 [:method: HEAD]
> * h2h3 [:path: /]
> * h2h3 [:scheme: https]
> * h2h3 [:authority: yandex.ru]
> * h2h3 [user-agent: curl/7.87.0]
> * h2h3 [accept: */*]
> * Using Stream ID: 1 (easy handle 0x2af18931fa0)
> } [5 bytes data]
> > HEAD / HTTP/2
> > Host: yandex.ru
> > user-agent: curl/7.87.0
> > accept: */*
> >
> { [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Newsession Ticket (4):
> { [233 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Newsession Ticket (4):
> { [233 bytes data]
> * old SSL session ID is stale, removing
> { [5 bytes data]
> * Connection state changed (MAX_CONCURRENT_STREAMS == 128)!
> } [5 bytes data]
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0< HTTP/2 302
> < location: https://dzen.ru/?yredirect=true
> < date: Tue, 12 Sep 2023 19:29:30 GMT
> < nel: {"report_to": "network-errors", "max_age": 100, "success_fraction": 0.001, "failure_fraction": 0.1}
> < x-content-type-options: nosniff
> < portal: Home
> < set-cookie: is_gdpr=0; Path=/; Domain=.yandex.ru; Expires=Thu, 11 Sep 2025 19:29:30 GMT
> < set-cookie: is_gdpr_b=COj6IhCGzgEoAg; Path=/; Domain=.yandex.ru; Expires=Thu, 11 Sep 2025 19:29:30 GMT
> < set-cookie: _yasc=WpMMZRFhovTxjiH63o/z1AkdITZD+ECG+6O24czLW4er3UCrhqTAgKJaUsQFtx05UGnF; domain=.yandex.ru; path=/; expires=Fri, 09 Sep 2033 19:29:30 GMT; secure
> < set-cookie: i=62tB50hYb32FPQm+rlyb3xjjtJCVH/ktRvwzJUG4VdKFLfEdZ+ZQq4xXxM1t7mXxvqXaAU+yBE8SseTJCyCtBSOI0/s=; Expires=Thu, 11-Sep-2025 19:29:30 GMT; Domain=.yandex.ru; Path=/; Secure; HttpOnly
> < set-cookie: yandexuid=7836185621694546970; Expires=Thu, 11-Sep-2025 19:29:30 GMT; Domain=.yandex.ru; Path=/; Secure
> < p3p: policyref="/w3c/p3p.xml", CP="NON DSP ADM DEV PSD IVDo OUR IND STP PHY PRE NAV UNI"
> < x-yandex-req-id: 1694546970075759-3709805628383618562-balancer-l7leveler-kubr-yp-sas-89-BAL-1771
> < accept-ch: Sec-CH-UA-Platform-Version, Sec-CH-UA-Mobile, Sec-CH-UA-Model, Sec-CH-UA, Sec-CH-UA-Full-Version-List, Sec-CH-UA-WoW64, Sec-CH-UA-Arch, Sec-CH-UA-Bitness, Sec-CH-UA-Platform, Sec-CH-UA-Full-Version, Viewport-Width, DPR, Device-Memory, RTT, Downlink, ECT
> < report-to: { "group": "network-errors", "max_age": 100, "endpoints": [{"url": "https://dr.yandex.net/nel", "priority": 1}, {"url": "https://dr2.yandex.net/nel", "priority": 2}]}
> < cache-control: max-age=1209600,private
> < x-robots-tag: unavailable_after: 12 Sep 2022 00:00:00 PST
> <
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/2 302
> location: https://dzen.ru/?yredirect=true
> date: Tue, 12 Sep 2023 19:29:30 GMT
> nel: {"report_to": "network-errors", "max_age": 100, "success_fraction": 0.001, "failure_fraction": 0.1}
> x-content-type-options: nosniff
> portal: Home
> set-cookie: is_gdpr=0; Path=/; Domain=.yandex.ru; Expires=Thu, 11 Sep 2025 19:29:30 GMT
> set-cookie: is_gdpr_b=COj6IhCGzgEoAg; Path=/; Domain=.yandex.ru; Expires=Thu, 11 Sep 2025 19:29:30 GMT
> set-cookie: _yasc=WpMMZRFhovTxjiH6234234234CG+6O24czLW4er3UCrhqTAgKJaUsQFtx05UGnF; domain=.yandex.ru; path=/; expires=Fri, 09 Sep 2033 19:29:30 GMT; secure
> set-cookie: i=62tB50hYb32FPQm+rly23JCVH/kt2342345G4VdKFLfEdZ+ZQq4xXxM1t7mXxvqXaAU+yBE8SseTJCyCtBSOI0/s=; Expires=Thu, 11-Sep-2025 19:29:30 GMT; Domain=.yandex.ru; Path=/; Secure; HttpOnly
> set-cookie: yandexuid=7836185621694546970; Expires=Thu, 11-Sep-2025 19:29:30 GMT; Domain=.yandex.ru; Path=/; Secure
> p3p: policyref="/w3c/p3p.xml", CP="NON DSP ADM DEV PSD IVDo OUR IND STP PHY PRE NAV UNI"
> x-yandex-req-id: 1694546970075759-3709805628383618562-balancer-l7leveler-kubr-yp-sas-89-BAL-1771
> accept-ch: Sec-CH-UA-Platform-Version, Sec-CH-UA-Mobile, Sec-CH-UA-Model, Sec-CH-UA, Sec-CH-UA-Full-Version-List, Sec-CH-UA-WoW64, Sec-CH-UA-Arch, Sec-CH-UA-Bitness, Sec-CH-UA-Platform, Sec-CH-UA-Full-Version, Viewport-Width, DPR, Device-Memory, RTT, Downlink, ECT
> report-to: { "group": "network-errors", "max_age": 100, "endpoints": [{"url": "https://dr.yandex.net/nel", "priority": 1}, {"url": "https://dr2.yandex.net/nel", "priority": 2}]}
> cache-control: max-age=1209600,private
> x-robots-tag: unavailable_after: 12 Sep 2022 00:00:00 PST
>```
>
>  __Info:__
> - Ip: ``77.88.55.60``
> - Port: ``443``
> - Host: ``yandex.ru``
> - Cache-Control: ``max-age=1209600,private``
> - Content-Type: ``nosniff``
> - Response code: ``302 - The resource has been temporarily moved.``
> - Protocol: ``HTTP/2``
> - Use SSL: ``TLSv1.3``

## Site: [python](https://www.python.org/)
#### Results for: https://www.python.org/
> __Use:__
> ```shell
> curl -4vI https://www.python.org/
>```
>__Result:__
>```shell
>    % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                  Dload  Upload   Total   Spent    Left  Speed
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 146.75.116.223:443...
> * Connected to www.python.org (146.75.116.223) port 443 (#0)
> * ALPN: offers h2
> * ALPN: offers http/1.1
> *  CAfile: C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
> *  CApath: none
> } [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Client hello (1):
> } [512 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Server hello (2):
> { [122 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Encrypted Extensions (8):
> { [19 bytes data]
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0* [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Certificate (11):
> { [2906 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, CERT verify (15):
> { [264 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Finished (20):
> { [52 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS change cipher, Change cipher spec (1):
> } [1 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Finished (20):
> } [52 bytes data]
> * SSL connection using TLSv1.3 / TLS_AES_256_GCM_SHA384
> * ALPN: server accepted h2
> * Server certificate:
> *  subject: CN=www.python.org
> *  start date: Jun 29 16:48:43 2023 GMT
> *  expire date: Jul 30 16:48:42 2024 GMT
> *  subjectAltName: host "www.python.org" matched cert's "www.python.org"
> *  issuer: C=BE; O=GlobalSign nv-sa; CN=GlobalSign Atlas R3 DV TLS CA 2023 Q2
> *  SSL certificate verify ok.
> * Using HTTP2, server supports multiplexing
> * Copying HTTP/2 data in stream buffer to connection buffer after upgrade: len=0
> } [5 bytes data]
> * h2h3 [:method: HEAD]
> * h2h3 [:path: /]
> * h2h3 [:scheme: https]
> * h2h3 [:authority: www.python.org]
> * h2h3 [user-agent: curl/7.87.0]
> * h2h3 [accept: */*]
> * Using Stream ID: 1 (easy handle 0x1d3e8111fa0)
> } [5 bytes data]
> > HEAD / HTTP/2
> > Host: www.python.org
> > user-agent: curl/7.87.0
> > accept: */*
> >
> { [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Newsession Ticket (4):
> { [209 bytes data]
> < HTTP/2 200
> < server: nginx
> < content-type: text/html; charset=utf-8
> < x-frame-options: SAMEORIGIN
> < via: 1.1 vegur, 1.1 varnish, 1.1 varnish
> < accept-ranges: bytes
> < date: Tue, 12 Sep 2023 19:36:13 GMT
> < age: 2754
> < x-served-by: cache-iad-kiad7000025-IAD, cache-fra-eddf8230055-FRA
> < x-cache: HIT, HIT
> < x-cache-hits: 1, 7
> < x-timer: S1694547373.280813,VS0,VE0
> < vary: Cookie
> < strict-transport-security: max-age=63072000; includeSubDomains; preload
> < content-length: 50558
> <
>   0 50558    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/2 200
> server: nginx
> content-type: text/html; charset=utf-8
> x-frame-options: SAMEORIGIN
> via: 1.1 vegur, 1.1 varnish, 1.1 varnish
> accept-ranges: bytes
> date: Tue, 12 Sep 2023 19:36:13 GMT
> age: 2754
> x-served-by: cache-iad-kiad70111025-IAD, cache-fra-eddf82111055-FRA
> x-cache: HIT, HIT
> x-cache-hits: 1, 7
> x-timer: S1694547373.280813,VS0,VE0
> vary: Cookie
> strict-transport-security: max-age=63072000; includeSubDomains; preload
> content-length: 50558
>```
>
>  __Info:__
> - Ip: ``146.75.116.223``
> - Port: ``443``
> - Host: ``www.python.org``
> - Cache-Control: ``-``
> - Content-Type: ``text/html; charset=utf-8``
> - Response code: ``200 - OK. The client's request was completed successfully.``
> - Protocol: ``HTTP/2``
> - Use SSL: ``TLSv1.3``

## Site: [GIT](https://git-scm.com/)
#### Results for: https://git-scm.com/
> __Use:__
> ```shell
> curl -4vI https://git-scm.com/
>```
>__Result:__
>```shell
>  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                  Dload  Upload   Total   Spent    Left  Speed
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 188.114.98.224:443...
> * Connected to git-scm.com (188.114.98.224) port 443 (#0)
> * ALPN: offers h2
> * ALPN: offers http/1.1
> *  CAfile: C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
> *  CApath: none
> } [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Client hello (1):
> } [512 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Server hello (2):
> { [122 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Encrypted Extensions (8):
> { [19 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Certificate (11):
> { [2334 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, CERT verify (15):
> { [78 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Finished (20):
> { [52 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS change cipher, Change cipher spec (1):
> } [1 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Finished (20):
> } [52 bytes data]
> * SSL connection using TLSv1.3 / TLS_AES_256_GCM_SHA384
> * ALPN: server accepted h2
> * Server certificate:
> *  subject: C=US; ST=California; L=San Francisco; O=Cloudflare, Inc.; CN=sni.cloudflaressl.com
> *  start date: May 18 00:00:00 2023 GMT
> *  expire date: May 17 23:59:59 2024 GMT
> *  subjectAltName: host "git-scm.com" matched cert's "git-scm.com"
> *  issuer: C=US; O=Cloudflare, Inc.; CN=Cloudflare Inc ECC CA-3
> *  SSL certificate verify ok.
> * Using HTTP2, server supports multiplexing
> * Copying HTTP/2 data in stream buffer to connection buffer after upgrade: len=0
> } [5 bytes data]
> * h2h3 [:method: HEAD]
> * h2h3 [:path: /]
> * h2h3 [:scheme: https]
> * h2h3 [:authority: git-scm.com]
> * h2h3 [user-agent: curl/7.87.0]
> * h2h3 [accept: */*]
> * Using Stream ID: 1 (easy handle 0x1c6d67a1fa0)
> } [5 bytes data]
> > HEAD / HTTP/2
> > Host: git-scm.com
> > user-agent: curl/7.87.0
> > accept: */*
> >
> { [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Newsession Ticket (4):
> { [238 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Newsession Ticket (4):
> { [238 bytes data]
> * old SSL session ID is stale, removing
> { [5 bytes data]
> < HTTP/2 200
> < date: Tue, 12 Sep 2023 19:42:10 GMT
> < content-type: text/html; charset=utf-8
> < x-frame-options: SAMEORIGIN
> < x-xss-protection: 1; mode=block
> < x-content-type-options: nosniff
> < x-download-options: noopen
> < x-permitted-cross-domain-policies: none
> < referrer-policy: strict-origin-when-cross-origin
> < cache-control: public, max-age=14400
> < etag: W/"db69273d9410cbf4536e9d4b3a59685d"
> < x-request-id: 5b655b2f-128f-4205-940e-13860b4aaf19
> < x-runtime: 0.008824
> < via: 1.1 vegur
> < cf-cache-status: HIT
> < age: 2597
> < server: cloudflare
> < cf-ray: 805aa1d4aafb4e0f-HEL
> <
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/2 200
> date: Tue, 12 Sep 2023 19:42:10 GMT
> content-type: text/html; charset=utf-8
> x-frame-options: SAMEORIGIN
> x-xss-protection: 1; mode=block
> x-content-type-options: nosniff
> x-download-options: noopen
> x-permitted-cross-domain-policies: none
> referrer-policy: strict-origin-when-cross-origin
> cache-control: public, max-age=14400
> etag: W/"db69273d9410cbf4536e9d4b3a59685d"
> x-request-id: 5b655b2f-128f-4205-940e-13860b4aaf19
> x-runtime: 0.008824
> via: 1.1 vegur
> cf-cache-status: HIT
> age: 2597
> server: cloudflare
> cf-ray: 805aa1d4aafb4e0f-HEL
>```
>
>  __Info:__
> - Ip: ``188.114.98.224``
> - Port: ``443``
> - Host: ``git-scm.com``
> - Cache-Control: ``public, max-age=14400``
> - Content-Type: ``text/html; charset=utf-8``
> - Response code: ``200 - OK. The client's request was completed successfully.``
> - Protocol: ``HTTP/2``
> - Use SSL: ``TLSv1.3``

## Site: [jetbrains](https://www.jetbrains.com/)
#### Results for: https://www.jetbrains.com/
> __Use:__
> ```shell
> curl -4vI https://www.jetbrains.com/
>```
>__Result:__
>```shell
>  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                  Dload  Upload   Total   Spent    Left  Speed
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 13.33.243.7:443...
> * Connected to www.jetbrains.com (13.33.243.7) port 443 (#0)
> * ALPN: offers h2
> * ALPN: offers http/1.1
> *  CAfile: C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
> *  CApath: none
> } [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Client hello (1):
> } [512 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Server hello (2):
> { [122 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Encrypted Extensions (8):
> { [19 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Certificate (11):
> { [4960 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, CERT verify (15):
> { [264 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Finished (20):
> { [36 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS change cipher, Change cipher spec (1):
> } [1 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Finished (20):
> } [36 bytes data]
> * SSL connection using TLSv1.3 / TLS_AES_128_GCM_SHA256
> * ALPN: server accepted h2
> * Server certificate:
> *  subject: CN=www.jetbrains.com
> *  start date: Feb 28 00:00:00 2023 GMT
> *  expire date: Feb  9 23:59:59 2024 GMT
> *  subjectAltName: host "www.jetbrains.com" matched cert's "www.jetbrains.com"
> *  issuer: C=US; O=Amazon; CN=Amazon RSA 2048 M02
> *  SSL certificate verify ok.
> * Using HTTP2, server supports multiplexing
> * Copying HTTP/2 data in stream buffer to connection buffer after upgrade: len=0
> } [5 bytes data]
> * h2h3 [:method: HEAD]
> * h2h3 [:path: /]
> * h2h3 [:scheme: https]
> * h2h3 [:authority: www.jetbrains.com]
> * h2h3 [user-agent: curl/7.87.0]
> * h2h3 [accept: */*]
> * Using Stream ID: 1 (easy handle 0x27587702110)
> } [5 bytes data]
> > HEAD / HTTP/2
> > Host: www.jetbrains.com
> > user-agent: curl/7.87.0
> > accept: */*
> >
> { [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Newsession Ticket (4):
> { [124 bytes data]
> * Connection state changed (MAX_CONCURRENT_STREAMS == 128)!
> } [5 bytes data]
> < HTTP/2 200
> < content-type: text/html; charset=utf-8
> < content-length: 47113
> < date: Tue, 12 Sep 2023 19:40:27 GMT
> < server: nginx
> < x-content-type-options: nosniff
> < referrer-policy: same-origin
> < expires: Tue, 12 Sep 2023 19:40:27 GMT
> < cache-control: max-age=0
> < pragma: no-cache
> < x-frame-options: DENY
> < x-content-type-options: nosniff
> < x-xss-protection: 1; mode=block
> < strict-transport-security: max-age=31536000;
> < vary: Accept-Encoding
> < via: 1.1 752474607e5162b3278b647bb0ff3818.cloudfront.net (CloudFront)
> < alt-svc: h3=":443"; ma=86400
> < age: 268
> < set-cookie: cf_country-region=RU-ROS; Domain=jetbrains.com; Path=/; Secure
> < x-cache: Hit from cloudfront
> < x-amz-cf-pop: HEL50-C1
> < x-amz-cf-id: WFc_bpOngqt0LUrUak-eZCH_3fOLYuWonl8cgFH-GRodD-GEjeiHmQ==
> <
>   0 47113    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/2 200
> content-type: text/html; charset=utf-8
> content-length: 47113
> date: Tue, 12 Sep 2023 19:40:27 GMT
> server: nginx
> x-content-type-options: nosniff
> referrer-policy: same-origin
> expires: Tue, 12 Sep 2023 19:40:27 GMT
> cache-control: max-age=0
> pragma: no-cache
> x-frame-options: DENY
> x-content-type-options: nosniff
> x-xss-protection: 1; mode=block
> strict-transport-security: max-age=31536000;
> vary: Accept-Encoding
> via: 1.1 752474607e5162b3278b647bb0ff3818.cloudfront.net (CloudFront)
> alt-svc: h3=":443"; ma=86400
> age: 268
> set-cookie: cf_country-region=RU-ROS; Domain=jetbrains.com; Path=/; Secure
> x-cache: Hit from cloudfront
> x-amz-cf-pop: HEL50-C1
> x-amz-cf-id: WFc_bpOngqt0LUrUak-eZCH_3fOLYuWonl8cgFH-GRodD-GEjeiHmQ==
>```
>
>  __Info:__
> - Ip: ``13.33.243.7``
> - Port: ``443``
> - Host: ``www.jetbrains.com``
> - Cache-Control: ``max-age=0``
> - Content-Type: ``text/html; charset=utf-8``
> - Response code: ``200 - OK. The client's request was completed successfully.``
> - Protocol: ``HTTP/2``
> - Use SSL: ``TLSv1.3``

## Site: [VSC](https://code.visualstudio.com/)
#### Results for: https://code.visualstudio.com/
> __Use:__
> ```shell
> curl -4vI https://code.visualstudio.com/
>```
>__Result:__
>```shell
>  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
>                                  Dload  Upload   Total   Spent    Left  Speed
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0*   Trying 13.107.246.45:443...
> * Connected to code.visualstudio.com (13.107.246.45) port 443 (#0)
> * ALPN: offers h2
> * ALPN: offers http/1.1
> *  CAfile: C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
> *  CApath: none
> } [5 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (OUT), TLS handshake, Client hello (1):
> } [512 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.3 (IN), TLS handshake, Server hello (2):
> { [98 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Certificate (11):
> { [3689 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Server key exchange (12):
> { [365 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Server finished (14):
> { [4 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (OUT), TLS handshake, Client key exchange (16):
> } [102 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (OUT), TLS change cipher, Change cipher spec (1):
> } [1 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (OUT), TLS handshake, Finished (20):
> } [16 bytes data]
> * [CONN-0-0][CF-SSL] TLSv1.2 (IN), TLS handshake, Finished (20):
> { [16 bytes data]
> * SSL connection using TLSv1.2 / ECDHE-RSA-AES256-GCM-SHA384
> * ALPN: server accepted h2
> * Server certificate:
> *  subject: C=US; ST=WA; L=Redmond; O=Microsoft Corporation; CN=code.visualstudio.com
> *  start date: Jul  2 20:00:24 2023 GMT
> *  expire date: Dec 29 20:00:24 2023 GMT
> *  subjectAltName: host "code.visualstudio.com" matched cert's "code.visualstudio.com"
> *  issuer: C=US; O=Microsoft Corporation; CN=Microsoft Azure TLS Issuing CA 02
> *  SSL certificate verify ok.
> * Using HTTP2, server supports multiplexing
> * Copying HTTP/2 data in stream buffer to connection buffer after upgrade: len=0
> } [5 bytes data]
> * h2h3 [:method: HEAD]
> * h2h3 [:path: /]
> * h2h3 [:scheme: https]
> * h2h3 [:authority: code.visualstudio.com]
> * h2h3 [user-agent: curl/7.87.0]
> * h2h3 [accept: */*]
> * Using Stream ID: 1 (easy handle 0x25c7d1d2110)
> } [5 bytes data]
> > HEAD / HTTP/2
> > Host: code.visualstudio.com
> > user-agent: curl/7.87.0
> > accept: */*
> >
> { [5 bytes data]
>   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0< HTTP/2 200
> < content-length: 50213
> < content-type: text/html; charset=utf-8
> < accept-ranges: bytes
> < etag: W/"c425-XBxswsHoV0dlJCAKuBbwZ9s5rjQ"
> < strict-transport-security: max-age=31536000; includeSubDomains
> < content-security-policy: frame-ancestors 'self'
> < x-frame-options: SAMEORIGIN
> < x-xss-protection: 1; mode=block
> < x-content-type-options: nosniff
> < x-content-type-options: nosniff
> < x-powered-by: ASP.NET
> < x-azure-ref: 0UsAAZQAAAAAS4lPNayMuTpFobe1x87SIU1RPRURHRTE4MTAAYmU4N2RjNmQtNDBmOS00NWIwLTg4MTAtOTkxMDg3ZWY4YjI5
> < x-cache: CONFIG_NOCACHE
> < date: Tue, 12 Sep 2023 19:47:29 GMT
> <
>   0 50213    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0HTTP/2 200
> content-length: 50213
> content-type: text/html; charset=utf-8
> accept-ranges: bytes
> etag: W/"c425-XBxswsHoV0dlJCAKuBbwZ9s5rjQ"
> strict-transport-security: max-age=31536000; includeSubDomains
> content-security-policy: frame-ancestors 'self'
> x-frame-options: SAMEORIGIN
> x-xss-protection: 1; mode=block
> x-content-type-options: nosniff
> x-content-type-options: nosniff
> x-powered-by: ASP.NET
> x-azure-ref: 0UsAAZQAAAAAS4lPNayMuTpFobe1x87SIU1RPRURHRTE4MTAAYmU4N2RjNmQtNDBmOS00NWIwLTg4MTAtOTkxMDg3ZWY4YjI5
> x-cache: CONFIG_NOCACHE
> date: Tue, 12 Sep 2023 19:47:29 GMT
>```
>
>  __Info:__
> - Ip: ``13.107.246.45``
> - Port: ``443``
> - Host: ``code.visualstudio.com``
> - Cache-Control: ``CONFIG_NOCACHE``
> - Content-Type: ``text/html; charset=utf-8``
> - Response code: ``200 - OK. The client's request was completed successfully.``
> - Protocol: ``HTTP/2``
> - Use SSL: ``TLSv1.2``
