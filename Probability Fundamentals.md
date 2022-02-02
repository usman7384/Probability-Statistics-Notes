<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <meta name="mobile-web-app-capable" content="yes">
    <title>
        Probability Fundamentals - HackMD
    </title>
    <link rel="icon" type="image/png" href="https://hackmd.io/favicon.png">
    <link rel="apple-touch-icon" href="https://hackmd.io/apple-touch-icon.png">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha256-916EbMg70RQy9LHiGkXzG8hSg9EdNy97GazNG/aiY1w=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha256-eZrrJcwDc/3uDhsdt61sL2oOBY362qM3lon1gyExkL0=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ionicons/2.0.1/css/ionicons.min.css" integrity="sha256-3iu9jgsy9TpTwXKb7bNQzqWekRX7pPK+2OLj3R922fo=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/octicons/3.5.0/octicons.min.css" integrity="sha256-QiWfLIsCT02Sdwkogf6YMiQlj4NE84MKkzEMkZnMGdg=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.5.1/themes/prism.min.css" integrity="sha256-vtR0hSWRc3Tb26iuN2oZHt3KRUomwTufNIf5/4oeCyg=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@hackmd/emojify.js@2.1.0/dist/css/basic/emojify.min.css" integrity="sha256-UOrvMOsSDSrW6szVLe8ZDZezBxh5IoIfgTwdNDgTjiU=" crossorigin="anonymous" />
    <style>
        @import url(https://fonts.googleapis.com/css?family=Roboto:300,300i,400,400i,500,500i|Source+Code+Pro:300,400,500|Source+Sans+Pro:300,300i,400,400i,600,600i|Source+Serif+Pro&subset=latin-ext);.hljs{display:block;background:#fff;padding:.5em;color:#333;overflow-x:auto}.hljs-comment,.hljs-meta{color:#969896}.hljs-emphasis,.hljs-quote,.hljs-string,.hljs-strong,.hljs-template-variable,.hljs-variable{color:#df5000}.hljs-keyword,.hljs-selector-tag,.hljs-type{color:#a71d5d}.hljs-attribute,.hljs-bullet,.hljs-literal,.hljs-number,.hljs-symbol{color:#0086b3}.hljs-built_in,.hljs-builtin-name{color:#005cc5}.hljs-name,.hljs-section{color:#63a35c}.hljs-tag{color:#333}.hljs-attr,.hljs-selector-attr,.hljs-selector-class,.hljs-selector-id,.hljs-selector-pseudo,.hljs-title{color:#795da3}.hljs-addition{color:#55a532;background-color:#eaffea}.hljs-deletion{color:#bd2c00;background-color:#ffecec}.hljs-link{text-decoration:underline}.markdown-body{font-size:16px;line-height:1.5;word-wrap:break-word}.markdown-body:after,.markdown-body:before{display:table;content:""}.markdown-body:after{clear:both}.markdown-body>:first-child{margin-top:0!important}.markdown-body>:last-child{margin-bottom:0!important}.markdown-body a:not([href]){color:inherit;text-decoration:none}.markdown-body .absent{color:#c00}.markdown-body .anchor{float:left;padding-right:4px;margin-left:-20px;line-height:1}.markdown-body .anchor:focus{outline:none}.markdown-body blockquote,.markdown-body dl,.markdown-body ol,.markdown-body p,.markdown-body pre,.markdown-body table,.markdown-body ul{margin-top:0;margin-bottom:16px}.markdown-body hr{height:.25em;padding:0;margin:24px 0;background-color:#e7e7e7;border:0}.markdown-body blockquote{font-size:16px;padding:0 1em;color:#777;border-left:.25em solid #ddd}.markdown-body blockquote>:first-child{margin-top:0}.markdown-body blockquote>:last-child{margin-bottom:0}.markdown-body kbd,.popover kbd{display:inline-block;padding:3px 5px;font-size:11px;line-height:10px;color:#555;vertical-align:middle;background-color:#fcfcfc;border:1px solid #ccc;border-bottom-color:#bbb;border-radius:3px;box-shadow:inset 0 -1px 0 #bbb}.markdown-body .loweralpha{list-style-type:lower-alpha}.markdown-body h1,.markdown-body h2,.markdown-body h3,.markdown-body h4,.markdown-body h5,.markdown-body h6{margin-top:24px;margin-bottom:16px;font-weight:600;line-height:1.25}.markdown-body h1 .octicon-link,.markdown-body h2 .octicon-link,.markdown-body h3 .octicon-link,.markdown-body h4 .octicon-link,.markdown-body h5 .octicon-link,.markdown-body h6 .octicon-link{color:#000;vertical-align:middle;visibility:hidden}.markdown-body h1:hover .anchor,.markdown-body h2:hover .anchor,.markdown-body h3:hover .anchor,.markdown-body h4:hover .anchor,.markdown-body h5:hover .anchor,.markdown-body h6:hover .anchor{text-decoration:none}.markdown-body h1:hover .anchor .octicon-link,.markdown-body h2:hover .anchor .octicon-link,.markdown-body h3:hover .anchor .octicon-link,.markdown-body h4:hover .anchor .octicon-link,.markdown-body h5:hover .anchor .octicon-link,.markdown-body h6:hover .anchor .octicon-link{visibility:visible}.markdown-body h1 code,.markdown-body h1 tt,.markdown-body h2 code,.markdown-body h2 tt,.markdown-body h3 code,.markdown-body h3 tt,.markdown-body h4 code,.markdown-body h4 tt,.markdown-body h5 code,.markdown-body h5 tt,.markdown-body h6 code,.markdown-body h6 tt{font-size:inherit}.markdown-body h1{font-size:2em}.markdown-body h1,.markdown-body h2{padding-bottom:.3em;border-bottom:1px solid #eee}.markdown-body h2{font-size:1.5em}.markdown-body h3{font-size:1.25em}.markdown-body h4{font-size:1em}.markdown-body h5{font-size:.875em}.markdown-body h6{font-size:.85em;color:#777}.markdown-body ol,.markdown-body ul{padding-left:2em}.markdown-body ol.no-list,.markdown-body ul.no-list{padding:0;list-style-type:none}.markdown-body ol ol,.markdown-body ol ul,.markdown-body ul ol,.markdown-body ul ul{margin-top:0;margin-bottom:0}.markdown-body li>p{margin-top:16px}.markdown-body li+li{padding-top:.25em}.markdown-body dl{padding:0}.markdown-body dl dt{padding:0;margin-top:16px;font-size:1em;font-style:italic;font-weight:700}.markdown-body dl dd{padding:0 16px;margin-bottom:16px}.markdown-body table{display:block;width:100%;overflow:auto;word-break:normal;word-break:keep-all}.markdown-body table th{font-weight:700}.markdown-body table td,.markdown-body table th{padding:6px 13px;border:1px solid #ddd}.markdown-body table tr{background-color:#fff;border-top:1px solid #ccc}.markdown-body table tr:nth-child(2n){background-color:#f8f8f8}.markdown-body img{max-width:100%;box-sizing:content-box;background-color:#fff}.markdown-body img[align=right]{padding-left:20px}.markdown-body img[align=left]{padding-right:20px}.markdown-body .emoji{max-width:none;vertical-align:text-top;background-color:transparent}.markdown-body span.frame{display:block;overflow:hidden}.markdown-body span.frame>span{display:block;float:left;width:auto;padding:7px;margin:13px 0 0;overflow:hidden;border:1px solid #ddd}.markdown-body span.frame span img{display:block;float:left}.markdown-body span.frame span span{display:block;padding:5px 0 0;clear:both;color:#333}.markdown-body span.align-center{display:block;overflow:hidden;clear:both}.markdown-body span.align-center>span{display:block;margin:13px auto 0;overflow:hidden;text-align:center}.markdown-body span.align-center span img{margin:0 auto;text-align:center}.markdown-body span.align-right{display:block;overflow:hidden;clear:both}.markdown-body span.align-right>span{display:block;margin:13px 0 0;overflow:hidden;text-align:right}.markdown-body span.align-right span img{margin:0;text-align:right}.markdown-body span.float-left{display:block;float:left;margin-right:13px;overflow:hidden}.markdown-body span.float-left span{margin:13px 0 0}.markdown-body span.float-right{display:block;float:right;margin-left:13px;overflow:hidden}.markdown-body span.float-right>span{display:block;margin:13px auto 0;overflow:hidden;text-align:right}.markdown-body code,.markdown-body tt{padding:0;padding-top:.2em;padding-bottom:.2em;margin:0;font-size:85%;background-color:rgba(0,0,0,.04);border-radius:3px}.markdown-body code:after,.markdown-body code:before,.markdown-body tt:after,.markdown-body tt:before{letter-spacing:-.2em;content:"\00a0"}.markdown-body code br,.markdown-body tt br{display:none}.markdown-body del code{text-decoration:inherit}.markdown-body pre{word-wrap:normal}.markdown-body pre>code{padding:0;margin:0;font-size:100%;word-break:normal;white-space:pre;background:transparent;border:0}.markdown-body .highlight{margin-bottom:16px}.markdown-body .highlight pre{margin-bottom:0;word-break:normal}.markdown-body .highlight pre,.markdown-body pre{padding:16px;overflow:auto;font-size:85%;line-height:1.45;background-color:#f7f7f7;border-radius:3px}.markdown-body pre code,.markdown-body pre tt{display:inline;max-width:auto;padding:0;margin:0;overflow:visible;line-height:inherit;word-wrap:normal;background-color:transparent;border:0}.markdown-body pre code:after,.markdown-body pre code:before,.markdown-body pre tt:after,.markdown-body pre tt:before{content:normal}.markdown-body .csv-data td,.markdown-body .csv-data th{padding:5px;overflow:hidden;font-size:12px;line-height:1;text-align:left;white-space:nowrap}.markdown-body .csv-data .blob-line-num{padding:10px 8px 9px;text-align:right;background:#fff;border:0}.markdown-body .csv-data tr{border-top:0}.markdown-body .csv-data th{font-weight:700;background:#f8f8f8;border-top:0}.news .alert .markdown-body blockquote{padding:0 0 0 40px;border:0 none}.activity-tab .news .alert .commits,.activity-tab .news .markdown-body blockquote{padding-left:0}.task-list-item{list-style-type:none}.task-list-item label{font-weight:400}.task-list-item.enabled label{cursor:pointer}.task-list-item+.task-list-item{margin-top:3px}.task-list-item-checkbox{float:left;margin:.31em 0 .2em -1.3em!important;vertical-align:middle;cursor:default!important}.markdown-body{padding-top:40px;padding-bottom:40px;max-width:758px;overflow:visible!important;position:relative}.markdown-body .emoji{vertical-align:top}.markdown-body pre{border:inherit!important}.markdown-body code{color:inherit!important}.markdown-body pre code .wrapper{display:-moz-inline-flex;display:-ms-inline-flex;display:-o-inline-flex;display:inline-flex}.markdown-body pre code .gutter{float:left;overflow:hidden;-webkit-user-select:none;user-select:none}.markdown-body pre code .gutter.linenumber{text-align:right;position:relative;display:inline-block;cursor:default;z-index:4;padding:0 8px 0 0;min-width:20px;box-sizing:content-box;color:#afafaf!important;border-right:3px solid #6ce26c!important}.markdown-body pre code .gutter.linenumber>span:before{content:attr(data-linenumber)}.markdown-body pre code .code{float:left;margin:0 0 0 16px}.markdown-body .gist .line-numbers{border-left:none;border-top:none;border-bottom:none}.markdown-body .gist .line-data{border:none}.markdown-body .gist table{border-spacing:0;border-collapse:inherit!important}.markdown-body code[data-gist-id]{background:none;padding:0}.markdown-body code[data-gist-id]:after,.markdown-body code[data-gist-id]:before{content:""}.markdown-body code[data-gist-id] .blob-num{border:unset}.markdown-body code[data-gist-id] table{overflow:unset;margin-bottom:unset}.markdown-body code[data-gist-id] table tr{background:unset}.markdown-body[dir=rtl] pre{direction:ltr}.markdown-body[dir=rtl] code{direction:ltr;unicode-bidi:embed}.markdown-body .alert>p:last-child{margin-bottom:0}.markdown-body pre.abc,.markdown-body pre.flow-chart,.markdown-body pre.graphviz,.markdown-body pre.mermaid,.markdown-body pre.sequence-diagram,.markdown-body pre.vega{text-align:center;background-color:inherit;border-radius:0;white-space:inherit;overflow:visible}.markdown-body pre.abc>code,.markdown-body pre.flow-chart>code,.markdown-body pre.graphviz>code,.markdown-body pre.mermaid>code,.markdown-body pre.sequence-diagram>code,.markdown-body pre.vega>code{text-align:left}.markdown-body pre.abc>svg,.markdown-body pre.flow-chart>svg,.markdown-body pre.graphviz>svg,.markdown-body pre.mermaid>svg,.markdown-body pre.sequence-diagram>svg,.markdown-body pre.vega>svg{max-width:100%;height:100%}.markdown-body pre>code.wrap{white-space:pre-wrap;white-space:-moz-pre-wrap;white-space:-pre-wrap;white-space:-o-pre-wrap;word-wrap:break-word}.markdown-body .alert>p:last-child,.markdown-body .alert>ul:last-child{margin-bottom:0}.markdown-body summary{display:list-item}.markdown-body summary:focus{outline:none}.markdown-body details summary{cursor:pointer}.markdown-body details:not([open])>:not(summary){display:none}.markdown-body figure{margin:1em 40px}.markdown-body .mark,.markdown-body mark{background-color:#fff1a7}.vimeo,.youtube{cursor:pointer;display:table;text-align:center;background-position:50%;background-repeat:no-repeat;background-size:contain;background-color:#000;overflow:hidden}.vimeo,.youtube{position:relative;width:100%}.youtube{padding-bottom:56.25%}.vimeo img{width:100%;object-fit:contain;z-index:0}.youtube img{object-fit:cover;z-index:0}.vimeo iframe,.youtube iframe,.youtube img{width:100%;height:100%;position:absolute;top:0;left:0}.vimeo iframe,.youtube iframe{vertical-align:middle;z-index:1}.vimeo .icon,.youtube .icon{position:absolute;height:auto;width:auto;top:50%;left:50%;transform:translate(-50%,-50%);color:#fff;opacity:.3;transition:opacity .2s;z-index:0}.vimeo:hover .icon,.youtube:hover .icon{opacity:.6;transition:opacity .2s}.slideshare .inner,.speakerdeck .inner{position:relative;width:100%}.slideshare .inner iframe,.speakerdeck .inner iframe{position:absolute;top:0;bottom:0;left:0;right:0;width:100%;height:100%}.figma{display:table;position:relative;width:100%;padding-bottom:56.25%}.figma iframe{position:absolute;top:0;bottom:0;left:0;right:0;width:100%;height:100%;border:1px solid #eee}.MJX_Assistive_MathML{display:none}#MathJax_Message{z-index:1000!important}.ui-infobar{position:relative;z-index:2;max-width:760px;margin:25px auto -25px;color:#777}.toc .invisable-node{list-style-type:none}.ui-toc{position:fixed;bottom:20px;z-index:998}.ui-toc.both-mode{margin-left:8px}.ui-toc.both-mode .ui-toc-label{height:40px;padding:10px 4px;border-top-left-radius:0;border-bottom-left-radius:0}.ui-toc-label{background-color:#e6e6e6;border:none;color:#868686;transition:opacity .2s}.ui-toc .open .ui-toc-label{opacity:1;color:#fff;transition:opacity .2s}.ui-toc-label:focus{opacity:.3;background-color:#ccc;color:#000}.ui-toc-label:hover{opacity:1;background-color:#ccc;transition:opacity .2s}.ui-toc-dropdown{margin-top:20px;margin-bottom:20px;padding-left:10px;padding-right:10px;max-width:45vw;width:25vw;max-height:70vh;overflow:auto;text-align:inherit}.ui-toc-dropdown>.toc{max-height:calc(70vh - 100px);overflow:auto}.ui-toc-dropdown[dir=rtl] .nav{padding-right:0;letter-spacing:.0029em}.ui-toc-dropdown a{overflow:hidden;text-overflow:ellipsis;white-space:pre}.ui-toc-dropdown .nav>li>a{display:block;padding:4px 20px;font-size:13px;font-weight:500;color:#767676}.ui-toc-dropdown .nav>li:first-child:last-child>ul,.ui-toc-dropdown .toc.expand ul{display:block}.ui-toc-dropdown .nav>li>a:focus,.ui-toc-dropdown .nav>li>a:hover{padding-left:19px;color:#000;text-decoration:none;background-color:transparent;border-left:1px solid #000}.ui-toc-dropdown[dir=rtl] .nav>li>a:focus,.ui-toc-dropdown[dir=rtl] .nav>li>a:hover{padding-right:19px;border-left:none;border-right:1px solid #000}.ui-toc-dropdown .nav>.active:focus>a,.ui-toc-dropdown .nav>.active:hover>a,.ui-toc-dropdown .nav>.active>a{padding-left:18px;font-weight:700;color:#000;background-color:transparent;border-left:2px solid #000}.ui-toc-dropdown[dir=rtl] .nav>.active:focus>a,.ui-toc-dropdown[dir=rtl] .nav>.active:hover>a,.ui-toc-dropdown[dir=rtl] .nav>.active>a{padding-right:18px;border-left:none;border-right:2px solid #000}.ui-toc-dropdown .nav .nav{display:none;padding-bottom:10px}.ui-toc-dropdown .nav>.active>ul{display:block}.ui-toc-dropdown .nav .nav>li>a{padding-top:1px;padding-bottom:1px;padding-left:30px;font-size:12px;font-weight:400}.ui-toc-dropdown[dir=rtl] .nav .nav>li>a{padding-right:30px}.ui-toc-dropdown .nav .nav>li>ul>li>a{padding-top:1px;padding-bottom:1px;padding-left:40px;font-size:12px;font-weight:400}.ui-toc-dropdown[dir=rtl] .nav .nav>li>ul>li>a{padding-right:40px}.ui-toc-dropdown .nav .nav>li>a:focus,.ui-toc-dropdown .nav .nav>li>a:hover{padding-left:29px}.ui-toc-dropdown[dir=rtl] .nav .nav>li>a:focus,.ui-toc-dropdown[dir=rtl] .nav .nav>li>a:hover{padding-right:29px}.ui-toc-dropdown .nav .nav>li>ul>li>a:focus,.ui-toc-dropdown .nav .nav>li>ul>li>a:hover{padding-left:39px}.ui-toc-dropdown[dir=rtl] .nav .nav>li>ul>li>a:focus,.ui-toc-dropdown[dir=rtl] .nav .nav>li>ul>li>a:hover{padding-right:39px}.ui-toc-dropdown .nav .nav>.active:focus>a,.ui-toc-dropdown .nav .nav>.active:hover>a,.ui-toc-dropdown .nav .nav>.active>a{padding-left:28px;font-weight:500}.ui-toc-dropdown[dir=rtl] .nav .nav>.active:focus>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active:hover>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active>a{padding-right:28px}.ui-toc-dropdown .nav .nav>.active>.nav>.active:focus>a,.ui-toc-dropdown .nav .nav>.active>.nav>.active:hover>a,.ui-toc-dropdown .nav .nav>.active>.nav>.active>a{padding-left:38px;font-weight:500}.ui-toc-dropdown[dir=rtl] .nav .nav>.active>.nav>.active:focus>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active>.nav>.active:hover>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active>.nav>.active>a{padding-right:38px}.markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,sans-serif}html[lang^=ja] .markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ\ ゴシック,sans-serif}html[lang=zh-tw] .markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif}html[lang=zh-cn] .markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif}html .markdown-body[lang^=ja]{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ\ ゴシック,sans-serif}html .markdown-body[lang=zh-tw]{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif}html .markdown-body[lang=zh-cn]{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif}html[lang^=ja] .ui-toc-dropdown{font-family:Source Sans Pro,Helvetica,Arial,Meiryo UI,MS PGothic,ＭＳ\ Ｐゴシック,sans-serif}html[lang=zh-tw] .ui-toc-dropdown{font-family:Source Sans Pro,Helvetica,Arial,Microsoft JhengHei UI,微軟正黑UI,sans-serif}html[lang=zh-cn] .ui-toc-dropdown{font-family:Source Sans Pro,Helvetica,Arial,Microsoft YaHei UI,微软雅黑UI,sans-serif}html .ui-toc-dropdown[lang^=ja]{font-family:Source Sans Pro,Helvetica,Arial,Meiryo UI,MS PGothic,ＭＳ\ Ｐゴシック,sans-serif}html .ui-toc-dropdown[lang=zh-tw]{font-family:Source Sans Pro,Helvetica,Arial,Microsoft JhengHei UI,微軟正黑UI,sans-serif}html .ui-toc-dropdown[lang=zh-cn]{font-family:Source Sans Pro,Helvetica,Arial,Microsoft YaHei UI,微软雅黑UI,sans-serif}.ui-affix-toc{position:fixed;top:0;max-width:15vw;max-height:70vh;overflow:auto}.back-to-top,.expand-toggle,.go-to-bottom{display:block;padding:4px 10px;margin-top:10px;margin-left:10px;font-size:12px;font-weight:500;color:#999}.back-to-top:focus,.back-to-top:hover,.expand-toggle:focus,.expand-toggle:hover,.go-to-bottom:focus,.go-to-bottom:hover{color:#563d7c;text-decoration:none}.back-to-top,.go-to-bottom{margin-top:0}.ui-user-icon{width:20px;height:20px;display:block;border-radius:50%;margin-top:2px;margin-bottom:2px;margin-right:5px;background-position:50%;background-repeat:no-repeat;background-size:cover}.ui-user-icon.small{width:18px;height:18px;display:inline-block;vertical-align:middle;margin:0 0 .2em}.ui-infobar>small>span{line-height:22px}.ui-infobar>small .dropdown{display:inline-block}.ui-infobar>small .dropdown a:focus,.ui-infobar>small .dropdown a:hover{text-decoration:none}.ui-more-info{color:#888;cursor:pointer;vertical-align:middle}.ui-more-info .fa{font-size:16px}.ui-connectedGithub,.ui-published-note{color:#888}.ui-connectedGithub{line-height:23px;white-space:nowrap}.ui-connectedGithub a.file-path{color:#888;text-decoration:none;padding-left:22px}.ui-connectedGithub a.file-path:active,.ui-connectedGithub a.file-path:hover{color:#888;text-decoration:underline}.ui-connectedGithub .fa{font-size:20px}.ui-published-note .fa{font-size:20px;vertical-align:top}.unselectable{-webkit-user-select:none;-o-user-select:none;user-select:none}.selectable{-webkit-user-select:text;-o-user-select:text;user-select:text}@media print{blockquote,div,img,pre,table{page-break-inside:avoid!important}a[href]:after{font-size:12px!important}}.markdown-body.slides{position:relative;z-index:1;color:#222}.markdown-body.slides:before{content:"";display:block;position:absolute;top:0;left:0;right:0;bottom:0;z-index:-1;background-color:currentColor;box-shadow:0 0 0 50vw}.markdown-body.slides section[data-markdown]{position:relative;margin-bottom:1.5em;background-color:#fff;text-align:center}.markdown-body.slides section[data-markdown] code{text-align:left}.markdown-body.slides section[data-markdown]:before{content:"";display:block;padding-bottom:56.23%}.markdown-body.slides section[data-markdown]>div:first-child{position:absolute;top:50%;left:1em;right:1em;transform:translateY(-50%);max-height:100%;overflow:hidden}.markdown-body.slides section[data-markdown]>ul{display:inline-block}.markdown-body.slides>section>section+section:after{content:"";position:absolute;top:-1.5em;right:1em;height:1.5em;border:3px solid #777}.site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,sans-serif}html[lang^=ja] .site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ\ ゴシック,sans-serif}html[lang=zh-tw] .site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif}html[lang=zh-cn] .site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif}body{font-smoothing:subpixel-antialiased!important;-webkit-font-smoothing:subpixel-antialiased!important;-moz-osx-font-smoothing:auto!important;text-shadow:0 0 1em transparent,1px 1px 1.2px rgba(0,0,0,.004);-webkit-overflow-scrolling:touch;letter-spacing:.025em;font-family:Source Sans Pro,Helvetica,Arial,sans-serif}html[lang^=ja] body{font-family:Source Sans Pro,Helvetica,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ\ ゴシック,sans-serif}html[lang=zh-tw] body{font-family:Source Sans Pro,Helvetica,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif}html[lang=zh-cn] body{font-family:Source Sans Pro,Helvetica,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif}abbr[title]{border-bottom:none;text-decoration:underline;-webkit-text-decoration:underline dotted;text-decoration:underline dotted}abbr[data-original-title],abbr[title]{cursor:help}body.modal-open{overflow-y:auto;padding-right:0!important}
    </style>
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
    	<script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js" integrity="sha256-3Jy/GbSLrg0o9y5Z5n1uw0qxZECH7C6OQpVBgNFYa0g=" crossorigin="anonymous"></script>
    	<script src="https://cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.min.js" integrity="sha256-g6iAfvZp+nDQ2TdTR/VVKJf3bGro4ub5fvWSWVRi2NE=" crossorigin="anonymous"></script>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/es5-shim/4.5.9/es5-shim.min.js" integrity="sha256-8E4Is26QH0bD52WoQpcB+R/tcWQtpzlCojrybUd7Mxo=" crossorigin="anonymous"></script>
    <![endif]-->
</head>

<body>
    <div id="doc" class="markdown-body container-fluid comment-enabled" data-hard-breaks="true"><h1 id="Probability-Fundamentals" data-id="Probability-Fundamentals"><a class="anchor hidden-xs" href="#Probability-Fundamentals" title="Probability-Fundamentals"><span class="octicon octicon-link"></span></a><span>Probability Fundamentals</span></h1><h2 id="Table-of-Contents" data-id="Table-of-Contents"><a class="anchor hidden-xs" href="#Table-of-Contents" title="Table-of-Contents"><span class="octicon octicon-link"></span></a><span>Table of Contents</span></h2><p><span class="toc"><ul>
<li><a href="#Probability-Fundamentals" title="Probability Fundamentals">Probability Fundamentals</a><ul>
<li><a href="#Table-of-Contents" title="Table of Contents">Table of Contents</a></li>
<li><a href="#Introduction" title="Introduction">Introduction</a></li>
<li><a href="#Starting-With-Probability" title="Starting With Probability">Starting With Probability</a><ul>
<li><a href="#Using-Outcomes" title="Using Outcomes">Using Outcomes</a></li>
<li><a href="#Outcome-Distributions" title="Outcome Distributions">Outcome Distributions</a></li>
<li><a href="#Complements" title="Complements">Complements</a></li>
<li><a href="#Expected-Value" title="Expected Value">Expected Value</a></li>
<li><a href="#Games-amp-Gambling" title="Games &amp; Gambling">Games &amp; Gambling</a></li>
</ul>
</li>
<li><a href="#Roll-the-Dice" title="Roll the Dice">Roll the Dice</a><ul>
<li><a href="#The-Rules-of-Sum-and-Product" title="The Rules of Sum and Product">The Rules of Sum and Product</a></li>
<li><a href="#Common-Intuitive-Fallacies" title="Common Intuitive Fallacies">Common Intuitive Fallacies</a></li>
<li><a href="#Complementary-Probabilities" title="Complementary Probabilities">Complementary Probabilities</a></li>
<li><a href="#Using-Symmetry" title="Using Symmetry">Using Symmetry</a></li>
<li><a href="#Endgame-Strategy" title="Endgame Strategy">Endgame Strategy</a></li>
</ul>
</li>
<li><a href="#Fairness-and-Expected-Value" title="Fairness and Expected Value">Fairness and Expected Value</a><ul>
<li><a href="#Introduction-to-Fairness" title="Introduction to Fairness">Introduction to Fairness</a></li>
<li><a href="#Barbotte" title="Barbotte">Barbotte</a></li>
<li><a href="#Roulette" title="Roulette">Roulette</a></li>
<li><a href="#Piglet" title="Piglet">Piglet</a></li>
<li><a href="#Linearity-of-Expectation" title="Linearity of Expectation">Linearity of Expectation</a></li>
<li><a href="#Bunco" title="Bunco">Bunco</a></li>
<li><a href="#Symmetry" title="Symmetry">Symmetry</a></li>
<li><a href="#Stein’s-Game" title="Stein’s Game">Stein’s Game</a></li>
<li><a href="#Information-Asymmetry" title="Information Asymmetry">Information Asymmetry</a></li>
</ul>
</li>
<li><a href="#Appendix-and-FAQ" title="Appendix and FAQ">Appendix and FAQ</a></li>
<li><a href="#References" title="References">References</a></li>
</ul>
</li>
</ul>
</span></p><h2 id="Introduction" data-id="Introduction"><a class="anchor hidden-xs" href="#Introduction" title="Introduction"><span class="octicon octicon-link"></span></a><span>Introduction</span></h2><p><strong><span>Probability</span></strong><span> is the likelihood of something happening. For example, A is likely to occur, B is definitely happening, there is a 40% chance of C, etc.</span></p><p><span>You’ll need to be able to work through paradoxes to make the best possible decisions and predictions when things are left up to random chance.</span></p><ul>
<li><span>Simpson’s Paradox</span><br>
<a href="https://www.britannica.com/topic/Simpsons-paradox" target="_blank" rel="noopener"><span>https://www.britannica.com/topic/Simpsons-paradox</span></a></li>
</ul><p><span>Probability lets us reason not only about the most likely future events but also about possible causes of past events.</span></p><h2 id="Starting-With-Probability" data-id="Starting-With-Probability"><a class="anchor hidden-xs" href="#Starting-With-Probability" title="Starting-With-Probability"><span class="octicon octicon-link"></span></a><span>Starting With Probability</span></h2><h3 id="Using-Outcomes" data-id="Using-Outcomes"><a class="anchor hidden-xs" href="#Using-Outcomes" title="Using-Outcomes"><span class="octicon octicon-link"></span></a><span>Using Outcomes</span></h3><p><img src="https://i.imgur.com/7bkzI4K.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/ICm2QzS.png" alt="" loading="lazy"><br>
<strong><span>Explanation</span></strong><br>
<span>Given the answer choices, it is much more likely that Katie, despite her past history, is only one of these rather than both of these. There is some probability that Katie does not help with the school’s music club. In addition, the event that Katie is both a teacher and helps with the music club is a subset of the event that Katie is a teacher. (A subset is a set contained within another set.) Thus, it cannot be more likely than the event that Katie is a teacher.</span></p><p><span>While we can’t predict most events with absolute certainty, we can try to estimate how likely they are to happen using probability.e.g. Usually, if I do not eat breakfast, I get a headache mid-morning. This morning I did not eat breakfast, so I will probably get a headache.This  statement somehow seems to be reasonable</span></p><p><img src="https://i.imgur.com/QenQ4xQ.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/1jqusRU.png" alt="" loading="lazy"><br>
<span>The sum of all of the probabilities for the different colors in each bag must sum to exactly 100%. It can’t be more than that.</span></p><p><span>Before diving any further into probability, let’s review some fundamental properties of probability:</span></p><ul>
<li><span>Probability is a number between 00 and 11, usually indicated with a capital P. For example, P(heads) indicates the probability of getting heads.</span></li>
<li><span>Probability can be expressed as a fraction, decimal, or percent.</span></li>
<li><span>The set of all possible outcomes is called the sample space. The sum of the probabilities of all outcomes in a sample space is exactly 1,1, or 100%.100%. For example, the probability of a coin landing on heads plus the probability of a coin landing on tails must equal exactly 11 because a coin cannot land on both heads and tails.</span></li>
<li><span>The most straightforward probability calculation is by outcomes. When there are some number of equally likely outcomes, the probability of a “successful” outcome can be calculated as --&gt; no. of successful Outcomes/no. of total Outcomes</span></li>
</ul><h3 id="Outcome-Distributions" data-id="Outcome-Distributions"><a class="anchor hidden-xs" href="#Outcome-Distributions" title="Outcome-Distributions"><span class="octicon octicon-link"></span></a><span>Outcome Distributions</span></h3><p><span>For some probability problems, it might be difficult to count all possible outcomes. For this reason, we represent the outcomes with lists and tables that make counting easier.</span><br>
<span>When faced with a tricky probability question, creating an outcome distribution chart can help show all of the possible outcomes.</span><br>
<em><span>Look at the example below:</span></em><br>
<img src="https://i.imgur.com/Q9aHzGm.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/LGOK2PH.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/90FDPbP.png" alt="" loading="lazy"></p><p><em><span>A handy solving technique in probability is to note when there is some sort of symmetry which causes two or more probabilities to be equal.</span></em></p><h3 id="Complements" data-id="Complements"><a class="anchor hidden-xs" href="#Complements" title="Complements"><span class="octicon octicon-link"></span></a><span>Complements</span></h3><p><span>Sometimes, it’s easier to count what did not happen than what did.</span><br>
<span>We explore how complements help us simplify and solve probability problems. Together, an event and its complement create all possible outcomes. The probability that something doesn’t happen is 11 minus the probability that it does happen.</span></p><p><span>We use complements to solve problems in probability. Because the probability that something happens and that it doesn’t happen add up to one, we can compute the one that’s easier to find.</span></p><h3 id="Expected-Value" data-id="Expected-Value"><a class="anchor hidden-xs" href="#Expected-Value" title="Expected-Value"><span class="octicon octicon-link"></span></a><span>Expected Value</span></h3><p><span>When making difficult decisions, we often consider best-possible and worst-possible outcomes. Is there a better way to make choices?</span><br>
<span>Now we’ll see how long-run averages can help us reason through making decisions when outcomes are uncertain.</span><br>
<span>The </span><strong><span>expected value</span></strong><span> (EV) is an anticipated value for an investment at some point in the future. In statistics and probability analysis, the expected value is calculated by multiplying each of the possible outcomes by the likelihood each outcome will occur and then summing all of those values.</span><br>
<em><span>Look at the example below:</span></em><br>
<img src="https://i.imgur.com/8AT96y8.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/MXbR4gi.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/oa1etnN.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/0h1rLVg.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/rtaxchO.png" alt="" loading="lazy"><br>
<em><span>We were trying to determine not only if we should expect to gain or lose money in the long run, but how much. This number is called expected value and tells us what to expect, on average, in the long run.</span></em></p><p><span>While we often can’t predict the consequences of our decisions, expected values let us see which choice would give us a better outcome in the long run.</span></p><h3 id="Games-amp-Gambling" data-id="Games-amp-Gambling"><a class="anchor hidden-xs" href="#Games-amp-Gambling" title="Games-amp-Gambling"><span class="octicon octicon-link"></span></a><span>Games &amp; Gambling</span></h3><p><span>Many gambling games are based on probability and expected values. We can apply the ideas we’ve been using to analyze outcomes for lotteries, coin tosses, and other games of pure chance.</span></p><h2 id="Roll-the-Dice" data-id="Roll-the-Dice"><a class="anchor hidden-xs" href="#Roll-the-Dice" title="Roll-the-Dice"><span class="octicon octicon-link"></span></a><span>Roll the Dice</span></h2><h3 id="The-Rules-of-Sum-and-Product" data-id="The-Rules-of-Sum-and-Product"><a class="anchor hidden-xs" href="#The-Rules-of-Sum-and-Product" title="The-Rules-of-Sum-and-Product"><span class="octicon octicon-link"></span></a><span>The Rules of Sum and Product</span></h3><ul>
<li><strong><span>The Rule of Product</span></strong><span>: When calculating the probability that multiple independent events will all occur, the probabilities are multiplied.</span><br>
<em><strong><span>Example:</span></strong></em><br>
<span>What is the chance of rolling a sum of 99 followed by a sum of 1010 on a pair of standard dice?</span><br>
<span>The probability of a sum of 9 is 4/36. The probability of a sum of 3/36.The overall probability of a 9 followed by a 10 is (4/36)*(3/36)</span><br>
<span>Because two die rolls do not affect each other (they are independent), multiplication is allowed.</span></li>
</ul><p><span>Two events are </span><em><strong><span>independent</span></strong></em><span> if the probability of one of them occurring does not affect the probability of the other occurring.</span></p><ul>
<li><strong><span>The Rule of Sum</span></strong><span>: the probability the event as a whole will occur is a sum of the probabilities of each individual part, as long as the parts cannot occur at the same time.</span></li>
</ul><p><span>A good rule of thumb (given independence) is the Rule of Product applies when an event </span><strong><span>and</span></strong><span> another event occur, while the Rule of Sum applies when an event </span><strong><span>or</span></strong><span> another event occurs.</span></p><h3 id="Common-Intuitive-Fallacies" data-id="Common-Intuitive-Fallacies"><a class="anchor hidden-xs" href="#Common-Intuitive-Fallacies" title="Common-Intuitive-Fallacies"><span class="octicon octicon-link"></span></a><span>Common Intuitive Fallacies</span></h3><p><span>The goal is to compare two events in each problem and identify the event that’s more likely.</span><br>
<span>Avoid the pitfalls of probability in situations where mistakes are common.</span></p><h3 id="Complementary-Probabilities" data-id="Complementary-Probabilities"><a class="anchor hidden-xs" href="#Complementary-Probabilities" title="Complementary-Probabilities"><span class="octicon octicon-link"></span></a><span>Complementary Probabilities</span></h3><p><span>In games with no possible draws, the probability of winning and the probability of losing add up to one. So, it’s enough to find just the simpler of the two!</span></p><p><span>The </span><strong><span>Rule of 1</span></strong><span> states that if the Rule of Sum is applied and every individual part of an event is accounted for, the probabilities ought to add up to 1, or 100%.</span></p><p><span>The </span><strong><span>complementary probability</span></strong><span> of an event is the probability that something </span><strong><span>doesn’t</span></strong><span> occur. Assuming there are only two choices (occurrence or non-occurrence) by the Rule of 1 the probability of an event not happening is 1 minus the probability of it happening. (Note: 1 also means 100% .)</span></p><p><strong><span>Example</span></strong><span>: If you know a certain strategy has a 10% chance of winning and there are no ties, it has a 100% - 10% = 90% chance of losing.</span></p><p><span>Finding the complementary probability — the probability of the opposite event — is easier than computing the relevant probability directly. Thanks to the rules of probability it’s enough to find one of them!</span></p><h3 id="Using-Symmetry" data-id="Using-Symmetry"><a class="anchor hidden-xs" href="#Using-Symmetry" title="Using-Symmetry"><span class="octicon octicon-link"></span></a><span>Using Symmetry</span></h3><p><span>Sometimes symmetry causes two or more probabilities to be equal, which reduces the number of overall probabilities you need to calculate.</span></p><p><img src="https://i.imgur.com/RIV2Y4h.png" alt="" loading="lazy"></p><p><span>In a number of dice games we found symmetry that made some probabilities equal. This useful shortcut allowed us to quickly solve these probability problems.</span></p><h3 id="Endgame-Strategy" data-id="Endgame-Strategy"><a class="anchor hidden-xs" href="#Endgame-Strategy" title="Endgame-Strategy"><span class="octicon octicon-link"></span></a><span>Endgame Strategy</span></h3><p><img src="https://i.imgur.com/R75D01h.png" alt="" loading="lazy"></p><p><span>In the game of Shut the Box, one needs to think ahead to find the optimal strategy.</span></p><p><img src="https://i.imgur.com/e1mcI2c.png" alt="" loading="lazy"></p><p><span>We saw that playing Shut the Box optimally comes down to comparing the probabilities of rolling different sums on a pair of dice.</span></p><h2 id="Fairness-and-Expected-Value" data-id="Fairness-and-Expected-Value"><a class="anchor hidden-xs" href="#Fairness-and-Expected-Value" title="Fairness-and-Expected-Value"><span class="octicon octicon-link"></span></a><span>Fairness and Expected Value</span></h2><h3 id="Introduction-to-Fairness" data-id="Introduction-to-Fairness"><a class="anchor hidden-xs" href="#Introduction-to-Fairness" title="Introduction-to-Fairness"><span class="octicon octicon-link"></span></a><span>Introduction to Fairness</span></h3><p><span>In a fair game, all players involved have an equal chance of winning, or if it’s a solo game, the player has an equal chance of winning and losing.</span></p><p><img src="https://i.imgur.com/08Y1DEr.png" alt="" loading="lazy"><br>
<span>If we determine a game is not entirely fair, we can try and determine what our chances are of winning. This can help us decide whether we want to play or not.</span></p><h3 id="Barbotte" data-id="Barbotte"><a class="anchor hidden-xs" href="#Barbotte" title="Barbotte"><span class="octicon octicon-link"></span></a><span>Barbotte</span></h3><p><span>In the game of Barbotte, each of the two players is assigned four winning combinations of two dice.</span></p><p><span>You are playing Barbotte with a friend using a pair of standard, six-sided dice. You take turns rolling both dice. According to the rules, you or your opponent win the round by rolling one of these four combinations: (3,3), (5,5), (6,6), or (6,5).</span></p><p><span>You lose the round if you or your opponent roll these combinations: (1,1), (2,2), (4,4), or (2,1). All other pairs result in neither a win nor a loss and the game continues.</span><br>
<span>You lose the round if you or your opponent roll these combinations: (1,1), (2,2), (4,4), or (2,1). All other pairs result in neither a win nor a loss and the game continues.</span></p><p><span>The game is fair two-fold: not only do you have an equal chance to win or lose against your opponent, but there are equal chances of rolling a winning or losing combo.</span></p><h3 id="Roulette" data-id="Roulette"><a class="anchor hidden-xs" href="#Roulette" title="Roulette"><span class="octicon octicon-link"></span></a><span>Roulette</span></h3><p><span>Roulette is a game of chance with many different kinds of bets.</span><br>
<img src="https://i.imgur.com/W0J4cZo.png" alt="" loading="lazy"><br>
<span>The “RED” bet wins on numbers colored red and “BLACK” bet wins on numbers colored black. They return 1:1 odds—that is, if a player wins, they win as much as they bet, doubling their money pile of that bet.</span></p><p><span>Is betting on red a fair bet? In other words, in the long run would you expect to break even betting on red only?</span><br>
<img src="https://i.imgur.com/uqWBjgQ.png" alt="" loading="lazy"></p><p><img src="https://i.imgur.com/Zn0RkFe.png" alt="" loading="lazy"></p><p><img src="https://i.imgur.com/PvXGMcI.png" alt="" loading="lazy"></p><p><span>We found that on average, roulette players are expected to lose money. This makes roulette an unfair game — the house is expected to win in the long run.</span></p><h3 id="Piglet" data-id="Piglet"><a class="anchor hidden-xs" href="#Piglet" title="Piglet"><span class="octicon octicon-link"></span></a><span>Piglet</span></h3><p><span>In the game of piglet, the player rolls a six-sided die and can either win or lose money depending on what they roll.</span></p><p><img src="https://i.imgur.com/VKkAiPH.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/guQGZNn.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/HcUhvfC.png" alt="" loading="lazy"></p><p><span>The key to winning the game of piglet is deciding when to quit and when to keep rolling the die. We established optimal strategies for different variations of the game using expected values.</span></p><h3 id="Linearity-of-Expectation" data-id="Linearity-of-Expectation"><a class="anchor hidden-xs" href="#Linearity-of-Expectation" title="Linearity-of-Expectation"><span class="octicon octicon-link"></span></a><span>Linearity of Expectation</span></h3><p><span>Linearity of expectation lets us compute the expected value of the sum of several outcomes, like the sum of dice rolls.</span></p><p><span>This concept is a general result called linearity of expectation. It means that if you are adding up two unknown quantities (for example the values of two dice), the expected value of their sum equals the sum of their expected values.</span></p><p><span>Thanks to the linearity of expectation, we can compute the expectation of a sum by adding individual expectations. This concept let us find the best strategy in a more complicated variation of the game of piglet.</span></p><h3 id="Bunco" data-id="Bunco"><a class="anchor hidden-xs" href="#Bunco" title="Bunco"><span class="octicon octicon-link"></span></a><span>Bunco</span></h3><p><span>Given a choice between different variations of the same game, one should pick the one with the highest expected value.</span><br>
<img src="https://i.imgur.com/mBCiKnZ.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/z11izA4.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/h78LNa3.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/WzUIBUa.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/jXeboBt.png" alt="" loading="lazy"></p><h3 id="Symmetry" data-id="Symmetry"><a class="anchor hidden-xs" href="#Symmetry" title="Symmetry"><span class="octicon octicon-link"></span></a><span>Symmetry</span></h3><p><span>When two or more outcomes are equally likely, you can take advantage of this to compute the expected value.</span></p><p><span>One of the most powerful arguments in probability and combinatorics is that of symmetry. If we can match up equally likely possibilities from two different cases, then we can say that these two cases have the same probability of happening.</span></p><p><span>This also works with expected value. For instance, because heads and tails are symmetric, if we flip many coins, we expect half of them to land on heads.</span></p><p><img src="https://i.imgur.com/bNhGmme.png" alt="" loading="lazy"></p><p><img src="https://i.imgur.com/2HvVv0g.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/28fAWbg.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/4HyjNdN.png" alt="" loading="lazy"></p><h3 id="Stein’s-Game" data-id="Stein’s-Game"><a class="anchor hidden-xs" href="#Stein’s-Game" title="Stein’s-Game"><span class="octicon octicon-link"></span></a><span>Stein’s Game</span></h3><p><span>Stein’s game can be played with different numbers of cards, and this choice impacts the probability of winning and the expected returns.</span></p><p><span>To play Stein’s game with NN cards, a dealer takes NN cards numbered 1, 2, \ldots, N1,2,…,N and shuffles them. Then, the player flips them over one by one, and they will be paid \dollar 1$1 every time a new highest card shows up. (The first card always counts as a highest card, since you haven’t seen any cards yet.)</span></p><p><img src="https://i.imgur.com/0HWC9vA.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/8iM6tX0.png" alt="" loading="lazy"></p><p><img src="https://i.imgur.com/PSxTGs4.png" alt="" loading="lazy"></p><h3 id="Information-Asymmetry" data-id="Information-Asymmetry"><a class="anchor hidden-xs" href="#Information-Asymmetry" title="Information-Asymmetry"><span class="octicon octicon-link"></span></a><span>Information Asymmetry</span></h3><p><span>The expected value of a game can be different depending on how much a player knows, and it can even change for the same person as they get more information.</span></p><p><span>In games, different players often have different information available to them. For example, in a game of poker, each player knows their own cards, but they do not know the other players’ cards.</span></p><p><span>This has a significant implication: the expected value of something can be different depending on how much you know, and it can even change for the same player as they get more information.</span></p><p><img src="https://i.imgur.com/Hsawqtq.png" alt="" loading="lazy"><br>
<img src="https://i.imgur.com/ujPPJwB.png" alt="" loading="lazy"></p><h2 id="Appendix-and-FAQ" data-id="Appendix-and-FAQ"><a class="anchor hidden-xs" href="#Appendix-and-FAQ" title="Appendix-and-FAQ"><span class="octicon octicon-link"></span></a><span>Appendix and FAQ</span></h2><div class="alert alert-info">
<p><strong><span>Find this document incomplete?</span></strong><span> Leave a comment!</span></p>
</div><h2 id="References" data-id="References"><a class="anchor hidden-xs" href="#References" title="References"><span class="octicon octicon-link"></span></a><span>References</span></h2><p><a href="https://brilliant.org/courses/probability-fundamentals/" target="_blank" rel="noopener"><span>https://brilliant.org/courses/probability-fundamentals/</span></a></p></div>
    <div class="ui-toc dropup unselectable hidden-print" style="display:none;">
        <div class="pull-right dropdown">
            <a id="tocLabel" class="ui-toc-label btn btn-default" data-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false" title="Table of content">
                <i class="fa fa-bars"></i>
            </a>
            <ul id="ui-toc" class="ui-toc-dropdown dropdown-menu" aria-labelledby="tocLabel">
                <div class="toc"><ul class="nav">
<li><a href="#Probability-Fundamentals" title="Probability Fundamentals">Probability Fundamentals</a><ul class="nav">
<li><a href="#Table-of-Contents" title="Table of Contents">Table of Contents</a></li>
<li><a href="#Introduction" title="Introduction">Introduction</a></li>
<li><a href="#Starting-With-Probability" title="Starting With Probability">Starting With Probability</a><ul class="nav">
<li><a href="#Using-Outcomes" title="Using Outcomes">Using Outcomes</a></li>
<li><a href="#Outcome-Distributions" title="Outcome Distributions">Outcome Distributions</a></li>
<li><a href="#Complements" title="Complements">Complements</a></li>
<li><a href="#Expected-Value" title="Expected Value">Expected Value</a></li>
<li><a href="#Games-amp-Gambling" title="Games &amp; Gambling">Games &amp; Gambling</a></li>
</ul>
</li>
<li><a href="#Roll-the-Dice" title="Roll the Dice">Roll the Dice</a><ul class="nav">
<li><a href="#The-Rules-of-Sum-and-Product" title="The Rules of Sum and Product">The Rules of Sum and Product</a></li>
<li><a href="#Common-Intuitive-Fallacies" title="Common Intuitive Fallacies">Common Intuitive Fallacies</a></li>
<li><a href="#Complementary-Probabilities" title="Complementary Probabilities">Complementary Probabilities</a></li>
<li><a href="#Using-Symmetry" title="Using Symmetry">Using Symmetry</a></li>
<li><a href="#Endgame-Strategy" title="Endgame Strategy">Endgame Strategy</a></li>
</ul>
</li>
<li><a href="#Fairness-and-Expected-Value" title="Fairness and Expected Value">Fairness and Expected Value</a><ul class="nav">
<li><a href="#Introduction-to-Fairness" title="Introduction to Fairness">Introduction to Fairness</a></li>
<li><a href="#Barbotte" title="Barbotte">Barbotte</a></li>
<li><a href="#Roulette" title="Roulette">Roulette</a></li>
<li><a href="#Piglet" title="Piglet">Piglet</a></li>
<li><a href="#Linearity-of-Expectation" title="Linearity of Expectation">Linearity of Expectation</a></li>
<li><a href="#Bunco" title="Bunco">Bunco</a></li>
<li><a href="#Symmetry" title="Symmetry">Symmetry</a></li>
<li><a href="#Stein’s-Game" title="Stein’s Game">Stein’s Game</a></li>
<li><a href="#Information-Asymmetry" title="Information Asymmetry">Information Asymmetry</a></li>
</ul>
</li>
<li><a href="#Appendix-and-FAQ" title="Appendix and FAQ">Appendix and FAQ</a></li>
<li><a href="#References" title="References">References</a></li>
</ul>
</li>
</ul>
</div><div class="toc-menu"><a class="expand-toggle" href="#">Expand all</a><a class="back-to-top" href="#">Back to top</a><a class="go-to-bottom" href="#">Go to bottom</a></div>
            </ul>
        </div>
    </div>
    <div id="ui-toc-affix" class="ui-affix-toc ui-toc-dropdown unselectable hidden-print" data-spy="affix" style="top:17px;display:none;" null null>
        <div class="toc"><ul class="nav">
<li><a href="#Probability-Fundamentals" title="Probability Fundamentals">Probability Fundamentals</a><ul class="nav">
<li><a href="#Table-of-Contents" title="Table of Contents">Table of Contents</a></li>
<li><a href="#Introduction" title="Introduction">Introduction</a></li>
<li><a href="#Starting-With-Probability" title="Starting With Probability">Starting With Probability</a><ul class="nav">
<li><a href="#Using-Outcomes" title="Using Outcomes">Using Outcomes</a></li>
<li><a href="#Outcome-Distributions" title="Outcome Distributions">Outcome Distributions</a></li>
<li><a href="#Complements" title="Complements">Complements</a></li>
<li><a href="#Expected-Value" title="Expected Value">Expected Value</a></li>
<li><a href="#Games-amp-Gambling" title="Games &amp; Gambling">Games &amp; Gambling</a></li>
</ul>
</li>
<li><a href="#Roll-the-Dice" title="Roll the Dice">Roll the Dice</a><ul class="nav">
<li><a href="#The-Rules-of-Sum-and-Product" title="The Rules of Sum and Product">The Rules of Sum and Product</a></li>
<li><a href="#Common-Intuitive-Fallacies" title="Common Intuitive Fallacies">Common Intuitive Fallacies</a></li>
<li><a href="#Complementary-Probabilities" title="Complementary Probabilities">Complementary Probabilities</a></li>
<li><a href="#Using-Symmetry" title="Using Symmetry">Using Symmetry</a></li>
<li><a href="#Endgame-Strategy" title="Endgame Strategy">Endgame Strategy</a></li>
</ul>
</li>
<li><a href="#Fairness-and-Expected-Value" title="Fairness and Expected Value">Fairness and Expected Value</a><ul class="nav">
<li><a href="#Introduction-to-Fairness" title="Introduction to Fairness">Introduction to Fairness</a></li>
<li><a href="#Barbotte" title="Barbotte">Barbotte</a></li>
<li><a href="#Roulette" title="Roulette">Roulette</a></li>
<li><a href="#Piglet" title="Piglet">Piglet</a></li>
<li><a href="#Linearity-of-Expectation" title="Linearity of Expectation">Linearity of Expectation</a></li>
<li><a href="#Bunco" title="Bunco">Bunco</a></li>
<li><a href="#Symmetry" title="Symmetry">Symmetry</a></li>
<li><a href="#Stein’s-Game" title="Stein’s Game">Stein’s Game</a></li>
<li><a href="#Information-Asymmetry" title="Information Asymmetry">Information Asymmetry</a></li>
</ul>
</li>
<li><a href="#Appendix-and-FAQ" title="Appendix and FAQ">Appendix and FAQ</a></li>
<li><a href="#References" title="References">References</a></li>
</ul>
</li>
</ul>
</div><div class="toc-menu"><a class="expand-toggle" href="#">Expand all</a><a class="back-to-top" href="#">Back to top</a><a class="go-to-bottom" href="#">Go to bottom</a></div>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js" integrity="sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha256-U5ZEeKfGNOja007MMD3YBI0A3OSZOQbeG6z2f2Y0hu8=" crossorigin="anonymous" defer></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gist-embed/2.6.0/gist-embed.min.js" integrity="sha256-KyF2D6xPIJUW5sUDSs93vWyZm+1RzIpKCexxElmxl8g=" crossorigin="anonymous" defer></script>
    <script>
        var markdown = $(".markdown-body");
        //smooth all hash trigger scrolling
        function smoothHashScroll() {
            var hashElements = $("a[href^='#']").toArray();
            for (var i = 0; i < hashElements.length; i++) {
                var element = hashElements[i];
                var $element = $(element);
                var hash = element.hash;
                if (hash) {
                    $element.on('click', function (e) {
                        // store hash
                        var hash = this.hash;
                        if ($(hash).length <= 0) return;
                        // prevent default anchor click behavior
                        e.preventDefault();
                        // animate
                        $('body, html').stop(true, true).animate({
                            scrollTop: $(hash).offset().top
                        }, 100, "linear", function () {
                            // when done, add hash to url
                            // (default click behaviour)
                            window.location.hash = hash;
                        });
                    });
                }
            }
        }

        smoothHashScroll();
        var toc = $('.ui-toc');
        var tocAffix = $('.ui-affix-toc');
        var tocDropdown = $('.ui-toc-dropdown');
        //toc
        tocDropdown.click(function (e) {
            e.stopPropagation();
        });

        var enoughForAffixToc = true;

        function generateScrollspy() {
            $(document.body).scrollspy({
                target: ''
            });
            $(document.body).scrollspy('refresh');
            if (enoughForAffixToc) {
                toc.hide();
                tocAffix.show();
            } else {
                tocAffix.hide();
                toc.show();
            }
            $(document.body).scroll();
        }

        function windowResize() {
            //toc right
            var paddingRight = parseFloat(markdown.css('padding-right'));
            var right = ($(window).width() - (markdown.offset().left + markdown.outerWidth() - paddingRight));
            toc.css('right', right + 'px');
            //affix toc left
            var newbool;
            var rightMargin = (markdown.parent().outerWidth() - markdown.outerWidth()) / 2;
            //for ipad or wider device
            if (rightMargin >= 133) {
                newbool = true;
                var affixLeftMargin = (tocAffix.outerWidth() - tocAffix.width()) / 2;
                var left = markdown.offset().left + markdown.outerWidth() - affixLeftMargin;
                tocAffix.css('left', left + 'px');
            } else {
                newbool = false;
            }
            if (newbool != enoughForAffixToc) {
                enoughForAffixToc = newbool;
                generateScrollspy();
            }
        }
        $(window).resize(function () {
            windowResize();
        });
        $(document).ready(function () {
            windowResize();
            generateScrollspy();
        });

        //remove hash
        function removeHash() {
            window.location.hash = '';
        }

        var backtotop = $('.back-to-top');
        var gotobottom = $('.go-to-bottom');

        backtotop.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            if (scrollToTop)
                scrollToTop();
            removeHash();
        });
        gotobottom.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            if (scrollToBottom)
                scrollToBottom();
            removeHash();
        });

        var toggle = $('.expand-toggle');
        var tocExpand = false;

        checkExpandToggle();
        toggle.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            tocExpand = !tocExpand;
            checkExpandToggle();
        })

        function checkExpandToggle () {
            var toc = $('.ui-toc-dropdown .toc');
            var toggle = $('.expand-toggle');
            if (!tocExpand) {
                toc.removeClass('expand');
                toggle.text('Expand all');
            } else {
                toc.addClass('expand');
                toggle.text('Collapse all');
            }
        }

        function scrollToTop() {
            $('body, html').stop(true, true).animate({
                scrollTop: 0
            }, 100, "linear");
        }

        function scrollToBottom() {
            $('body, html').stop(true, true).animate({
                scrollTop: $(document.body)[0].scrollHeight
            }, 100, "linear");
        }
    </script>
</body>

</html>
