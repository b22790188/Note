
## Flow

1. 透過常見前端框架撰寫程式碼(`react`、`vue`、`angular`)
2. 撰寫完成後，將框架程式碼編譯成瀏覽器可解析的`html`、`css`、`js`
3.  將這些編譯後的資源放到要deploy的server上。編譯好的檔案中，`html`、`css`、`js`會自動連結好，讓使用者能夠正常存取畫面。

## Node server

node server在整個流程中扮演的角色主要是方便我們在開發的過程中能進行快速的除錯以及調整，在正式環境中通常還是會將檔案先編譯後在放到server中。