# Settings User

```js
{
  // Emmet customization
  // http://docs.emmet.io/customization/

  // Emmet CSS completions 설정
  "css_completions_scope": "source.css - meta.selector.css - meta.property-value.css, source.scss - meta.selector.scss - meta.property-value.scss, source.sass - meta.selector.sass - meta.property-value.sass, source.less - meta.selector.css - meta.property-value.css",

  // 스니펫 사용자 정의
  // https://github.com/emmetio/emmet/blob/master/lib/snippets.json
  "snippets": {

    // Emmet 변수 설정
    // 주언어, 인코딩 설정
    "variables": {
      "lang": "ko",
      "locale": "ko-KR"
    },

    // HTML 사용자 정의
    "html": {
      // HTML 축약 표현식
      "abbreviations": {
        "btn": "button[type=button]",
        "btn:submit": "button[type=submit]",
        "btn:reset": "button[type=reset]",
      },
      // HTML 스니펫
      "snippets": {
        "cc:ie6": "<!--[if IE 6]>\n\t|\n<![endif]-->",
        "cc:ie7": "<!--[if IE 7]>\n\t|\n<![endif]-->",
        "cc:ie8": "<!--[if IE 8]>\n\t|\n<![endif]-->",
        "cc:ie9": "<!--[if IE 9]>\n\t|\n<![endif]-->",
        "cc:li-ie7": "<!--[if lt IE 7]>\n\t|\n<![endif]-->",
        "cc:li-ie8": "<!--[if lt IE 8]>\n\t|\n<![endif]-->",
        "cc:lt-ie9": "<!--[if lt IE 9]>\n\t|\n<![endif]-->",
        "cc:lie-ie7": "<!--[if lte IE 7]>\n\t|\n<![endif]-->",
        "cc:lie-ie8": "<!--[if lte IE 8]>\n\t|\n<![endif]-->",
        "cc:lte-ie9": "<!--[if lte IE 9]>\n\t|\n<![endif]-->",
        "cc:gt-ie6": "<!--[if gt IE 7]>\n\t|\n<![endif]-->",
        "cc:gt-ie7": "<!--[if gt IE 8]>\n\t|\n<![endif]-->",
        "cc:gt-ie8": "<!--[if gt IE 9]>\n\t|\n<![endif]-->",
        "cc:gte-ie6": "<!--[if gte IE 7]>\n\t|\n<![endif]-->",
        "cc:gte-ie7": "<!--[if gte IE 8]>\n\t|\n<![endif]-->",
        "cc:gte-ie8": "<!--[if gte IE 9]>\n\t|\n<![endif]-->",
        "cc:ie8-html": "<!--[if IE 8]><html lang=\"ko-KR\" class=\"ie lt-ie10 ie8 no-js\"><![endif]-->",
        "cc:ie9-html": "<!--[if IE 9]><html lang=\"ko-KR\" class=\"ie lt-ie10 ie9 no-js\"><![endif]-->",
        "cc:noie-html": "<!--[if !IE]><!-->\n<html lang=\"ko-KR\" class=\"no-js\">\n<!--<![endif]-->"
      }
    },

    // CSS 사용자 정의
    "css": {
      // CSS 스니펫
      "snippets": {
        "@charset": "@charset \"${1:utf-8}\";",
        "@c": "@charset \"${1:utf-8}\";",
        "@import": "@import url(|);",
        "@im": "@import url(|);",
        "@media": "@media ${1:screen} {\n\t|\n}",
        "@m": "@media ${1:screen} {\n\t|\n}",
        "@font-face": "@font-face {\n\tfont-family: |;\n\tsrc: url(|);\n}",
        "@f": "@font-face {\n\tfont-family: |;\n\tsrc: url(|);\n}",
        "@f+": "@font-face {\n\tfont-family: '${1:FontName}';\n\tsrc: url('${2:FileName}.eot');\n\tsrc: url('${2:FileName}.eot?#iefix') format('embedded-opentype'),\n\t\t url('${2:FileName}.woff') format('woff'),\n\t\t url('${2:FileName}.ttf') format('truetype'),\n\t\t url('${2:FileName}.svg#${1:FontName}') format('svg');\n\tfont-style: ${3:normal};\n\tfont-weight: ${4:normal};\n}",
        "@kf": "@-webkit-keyframes ${1:identifier} {\n\t${2:from} { ${3} }${6}\n\t${4:to} { ${5} }\n}\n@-o-keyframes ${1:identifier} {\n\t${2:from} { ${3} }${6}\n\t${4:to} { ${5} }\n}\n@-moz-keyframes ${1:identifier} {\n\t${2:from} { ${3} }${6}\n\t${4:to} { ${5} }\n}\n@keyframes ${1:identifier} {\n\t${2:from} { ${3} }${6}\n\t${4:to} { ${5} }\n}"
      }
    },

    // SCSS 사용자 정의
    "scss": {
      // SCSS 스니펫
      "snippets": {
        // Comment
        "@cmt": "// ------------------------------\n// ${1}\n// ------------------------------\n${0}",
        // Charset
        "@charset": "@charset '${1:utf-8}';",
        "@c": "@charset '${1:utf-8}';",
        // Import
        "@import": "@import '${1}';",
        "@im": "@import '${1}';",
        // Media
        "@media": "@media ${1:screen} {\n\t|\n}",
        "@m": "@media ${1:screen} {\n\t|\n}",
        // Font
        "@font-face": "@font-face {\n\tfont-family: |;\n\tsrc: url(|);\n}",
        "@f": "@font-face {\n\tfont-family: |;\n\tsrc: url(|);\n}",
        "@f+": "@font-face {\n\tfont-family: '${1:FontName}';\n\tsrc: url('${2:FileName}.eot');\n\tsrc: url('${2:FileName}.eot?#iefix') format('embedded-opentype'),\n\t\t url('${2:FileName}.woff') format('woff'),\n\t\t url('${2:FileName}.ttf') format('truetype'),\n\t\t url('${2:FileName}.svg#${1:FontName}') format('svg');\n\tfont-style: ${3:normal};\n\tfont-weight: ${4:normal};\n}",
        // Keyframe
        "@kf": "@-webkit-keyframes ${1:identifier} {\n\t${2:from} { ${3} }${6}\n\t${4:to} { ${5} }\n}\n@-o-keyframes ${1:identifier} {\n\t${2:from} { ${3} }${6}\n\t${4:to} { ${5} }\n}\n@-moz-keyframes ${1:identifier} {\n\t${2:from} { ${3} }${6}\n\t${4:to} { ${5} }\n}\n@keyframes ${1:identifier} {\n\t${2:from} { ${3} }${6}\n\t${4:to} { ${5} }\n}",
        // Extend
        "@extend": "@extend ${1};",
        "@e": "@extend ${1};",
        // Mixin
        "@mixin": "@mixin ${1:name}(${2:args}) {\n\t${0}\n}",
        "@mx": "@mixin ${1:name}(${2:args}) {\n\t${0}\n}",
        // Include
        "@include": "@include ${1:${2:name}(${3:args});}",
        "@in": "@include ${1:${2:name}(${3:args});}",
        // Content
        "@content": "@content;",
        "@cnt": "@content;",
        // Function
        "@function": "@function ${1:name}(${2:args}) {\n\t${0}\n\t@return args;\n}",
        "@fn": "@function ${1:name}(${2:args}) {\n\t${0}\n\t@return args;\n}",
        // Return
        "@return": "@return ${1};",
        "@r": "@return ${1};",
        // Condition
        "@if": "@if (${1:true}) {\n\t${0}\n}",
        "@elseif": "@else if (${1:true}) {\n\t${0}\n}",
        "@else": "@else {\n\t${0}\n}",
        // Loop
        "@while": "\\$i: 1;\n@while (\\$i <= ${1:12}) {\n\t${0}\n\t\\$i: \\$i + 1;\n}",
        "@for": "@for \\$i from 1 ${1:[through\\|to]} ${2:12} {\n\t${0}\n}",
        "@each": "@each \\$obj in ${1:([List\\|Map])} {\n\t${0}\n}"
      }
    },

    // Sass 사용자 정의
    "sass": {
      // Sass 스니펫
      "snippets": {
        // Comment
        "@cmt": "// ------------------------------\n// ${1}\n// ------------------------------\n${0}",
        // Charset
        "@charset": "@charset ${1:utf-8}",
        "@c": "@charset ${1:utf-8}",
        // Import
        "@import": "@import ",
        "@im": "@import ",
        // Media
        "@media": "@media ${1:screen}\n\t|\n",
        "@m": "@media ${1:screen}\n\t|\n",
        // Font
        "@font-face": "@font-face\n\tfont-family: |\n\tsrc: url(|)\n",
        "@f": "@font-face\n\tfont-family: |\n\tsrc: url(|)\n",
        "@f+": "@font-face \n\tfont-family: '${1:FontName}'\n\tsrc: url('${2:FileName}.eot')\n\tsrc: url('${2:FileName}.eot?#iefix') format('embedded-opentype'),\n\t\t url('${2:FileName}.woff') format('woff'),\n\t\t url('${2:FileName}.ttf') format('truetype'),\n\t\t url('${2:FileName}.svg#${1:FontName}') format('svg')\n\tfont-style: ${3:normal}\n\tfont-weight: ${4:normal}\n",
        // Keyframe
        "@kf": "@-webkit-keyframes ${1:identifier}\n\t${2:from}\n\t\t${3}\n\t${4:to}\n\t\t${5}\n\n@-o-keyframes ${1:identifier}\n\t${2:from}\n\t\t${3}\n\t${4:to}\n\t\t${5}\n\n@-moz-keyframes ${1:identifier}\n\t${2:from}\n\t\t${3}\n\t${4:to}\n\t\t${5}\n\n@keyframes ${1:identifier}\n\t${2:from}\n\t\t${3}\n\t${4:to}\n\t\t${5}\n",
        // Extend
        "@extend": "@extend ",
        "@e": "@extend ",
        // Mixin
        "@mixin": "=${1:name}(${2:args})\n\t${0}",
        "@mx": "=${1:name}(${2:args})\n\t${0}",
        // Content
        "@content": "@content",
        "@cnt": "@content",
        // Function
        "@function": "@function ${1:name}(${2:args})\n\t${0}\n\t@return args",
        "@fn": "@function ${1:name}(${2:args})\n\t${0}\n\t@return args",
        // Return
        "@return": "@return ",
        "@r": "@return ",
        // Condition
        "@if": "@if (${1:true})\n\t${0}",
        "@elseif": "@else if (${1:true})\n\t${0}",
        "@else": "@else\n\t${0}",
        // Loop
        "@while": "\\$i: 1\n@while (\\$i <= ${1:12})\n\t${0}\n\t\\$i: \\$i + 1",
        "@for": "@for \\$i from 1 ${1:[through\\|to]} ${2:12}\n\t${0}",
        "@each": "@each \\$obj in ${1:([List\\|Map])}\n\t${0}"
      }
    }
  },

  // Emmet 환경 설정
  // http://docs.emmet.io/customization/preferences/
  "preferences": {
    // 시작/끝 지점에 코멘트 추가(|c)
    "filter.commentBefore": "<!-- Start: <%= attr('id', '#')%><%= attr('class', '.')%> -->\n",
    "filter.commentAfter": "\n<!-- End: <%= attr('id', '#')%><%= attr('class', '.')%> -->"
  },

  // 문법 모드 출력 설정
  // http://docs.emmet.io/customization/syntax-profiles/
  "syntaxProfiles": {}
}
```