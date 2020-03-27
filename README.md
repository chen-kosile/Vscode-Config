# Vscode-Config
// 将设置放入此文件中以覆盖默认设置
{
  "files.autoSave": "off",
  "files.autoSaveDelay": 1500,
  "editor.tabSize": 2,
  // 关闭快速预览
  "editor.minimap.enabled": true,
  "editor.wordWrap": "on",
  "editor.lineNumbers": "on",
  "editor.quickSuggestions": {
    "other": true,
    "comments": true,
    "strings": true
  },
  // bug控制缩进不关tabSize修改无用
  "editor.detectIndentation": false,
  // 保存格式化
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    // "source.organizeImports": true,
    "source.fixAll": true,
    "source.fixAll.eslint": true
  },
  // eslint 配置
  "eslint.options": {
    "extensions": ["js", ".vue"]
  },
  "eslint.format.enable": true,
  "eslint.validate": ["vue", "html", "javascript", "javascriptreact", "jsx", "typescript"],
  "prettier.semi": false,
  "prettier.singleQuote": true,
  "prettier.printWidth": 100,
  "prettier.packageManager": "yarn",
  "prettier.spaceBeforeFunctionParen": true,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  // 参考线
  "workbench.colorTheme": "Bluloco Dark",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.editor.enablePreview": false,
  "emmet.triggerExpansionOnTab": true,
  "emmet.includeLanguages": {
    "vue-html": "html",
    "javascript": "javascriptreact",
    "wxml": "html"
  },
  // 搜索配置
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/dist": true
  },
  "gitlens.keymap": "alternate",
  "explorer.confirmDragAndDrop": false,
  "vetur.format.defaultFormatter.html": "prettyhtml",
  "vetur.format.defaultFormatter.js": "prettier-eslint",
  "vetur.format.defaultFormatterOptions": {
    "prettyhtml": {
      "printWidth": 80, // No line exceeds 100 characters
      "singleQuote": false // Prefer double quotes over single quotes
    },
    "prettier": {
      "semi": false,
      "singleQuote": true,
      "eslintIntegration": true,
      "parser": "babylon"
    }
  },
  "javascript.implicitProjectConfig.experimentalDecorators": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "files.associations": {
    "*.cjson": "jsonc",
    "*.wxss": "css",
    "*.wxs": "javascript"
  },
  "minapp-vscode.disableAutoConfig": true,
  "gitlens.advanced.messages": {
    "suppressShowKeyBindingsNotice": true
  },
  "highlight-matching-tag.styles": {
    "opening": {
      "left": {
        "custom": {
          "borderWidth": "0 0 0 4px",
          "borderStyle": "solid",
          "borderColor": "LightSkyBlue",
          "borderRadius": "5px"
        }
      },
      "right": {
        "custom": {
          "borderWidth": "0 4px 0 0",
          "borderStyle": "solid",
          "borderColor": "LightSkyBlue",
          "borderRadius": "5px"
        }
      }
    }
  },
  "less.compile": {
    "outExt": "wxss"
  },
  "typescript.updateImportsOnFileMove.enabled": "always"
}
