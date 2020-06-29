# LectureNotesOnHighSchoolPhysics

高中物理学讲义

使用<https://github.com/ElegantLaTeX/ElegantBook> 模板

顺便备份vscode的设置

{
  "workbench.colorTheme": "Monokai",
  "sync.gist": "b240146376477a450a64e5f364035bdb",
  "sync.autoDownload": true,
  "sync.autoUpload": true,
  "editor.tabSize": 2,
  "editor.renderControlCharacters": true,
  "editor.renderWhitespace": "all",
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "markdownlint.config": {
    "MD029": false,
    "MD045": false
  },
  "explorer.confirmDragAndDrop": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.markdownlint": true
  },
  "window.zoomLevel": 0,
  "explorer.confirmDelete": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "python.dataScience.askForKernelRestart": false,
  "latex-workshop.latex.tools": [
    {
      "name": "latexmk",
      "command": "latexmk",
      "args": [
        "-synctex=1",
        "-interaction=nonstopmode",
        "-file-line-error",
        "-pdf",
        "%DOC%"
      ]
    },
    {
      "name": "xelatex",
      "command": "xelatex",
      "args": [
        "-synctex=1",
        "-interaction=nonstopmode",
        "-file-line-error",
        "%DOC%"
      ]
    },
    {
      "name": "pdflatex",
      "command": "pdflatex",
      "args": [
        "-synctex=1",
        "-interaction=nonstopmode",
        "-file-line-error",
        "%DOC%"
      ]
    },
    {
      "name": "bibtex",
      "command": "bibtex",
      "args": [
        "%DOCFILE%"
      ]
    }
  ],
  "latex-workshop.latex.recipes": [
    {
      "name": "xelatex",
      "tools": [
        "xelatex"
      ]
    },
    {
      "name": "latexmk",
      "tools": [
        "latexmk"
      ]
    },
    {
      "name": "pdflatex -> bibtex -> pdflatex*2",
      "tools": [
        "pdflatex",
        "bibtex",
        "pdflatex",
        "pdflatex"
      ]
    }
  ],
  "latex-workshop.latex.clean.fileTypes": [
    ".aux",
    ".bbl",
    ".blg",
    ".idx",
    ".ind",
    ".lof",
    ".lot",
    ".out",
    ".toc",
    ".acn",
    ".acr",
    ".alg",
    ".glg",
    ".glo",
    ".gls",
    ".ist",
    ".fls",
    ".log",
    "*.fdb_latexmk"
  ],
  "latex-workshop.view.pdf.viewer": "external",
  "latex-workshop.view.pdf.external.viewer.command": "/Applications/Skim.app/Contents/SharedSupport/displayline",
  "latex-workshop.view.pdf.external.viewer.args": [
    "-r",
    "0",
    "%PDF%"
  ],
  "latex-workshop.view.pdf.external.synctex.command": "/Applications/Skim.app/Contents/SharedSupport/displayline",
  "latex-workshop.view.pdf.external.synctex.args": [
    "-r",
    "%LINE%",
    "%PDF%",
    "%TEX%"
  ],
  "editor.wordWrap": "on",
  "workbench.startupEditor": "newUntitledFile",
  "workbench.iconTheme": "Monokai Pro (Filter Machine) Icons",
  "latex-workshop.synctex.afterBuild.enabled": true,
}
