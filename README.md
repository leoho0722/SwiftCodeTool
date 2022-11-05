# SwiftCodeTool

iOS App 開發練習 − 常用的 Function、Code Snippets、Xcode Template

## Code Snippets

使用方法：

1. Command + Q 關閉 Xcode
2. 打開 Finder
3. 前往 ```~/Library/Developer/Xcode/UserData/CodeSnippets```
4. 將 Swift Code Snippets 資料夾內副檔名為 ```.codesnippets``` 的檔案複製到該目錄底下
5. 在 Xcode 內舒服使用

## Xcode Template

Controller Previews.xctemplate 使用方法：

1. 打開 Finder
2. 前往 ```/Applications/Xcode.app/Contents/Developer/Library/Xcode/Templates```
3. 將 Xcode Template 資料夾內副檔名為 ```.xctemplate``` 的檔案複製到該目錄下
4. 在 Xcode 內 New -> File，滑到最底下選擇 Previews 模板
5. Controller 輸入要預覽畫面的 UIViewController class 名稱
6. 將檔名命名為 UIViewController class 名稱 + Previews 以方便辨認是哪個畫面的預覽 (Ex：MainViewControllerPreviews)
7. 即可在 UIKit 的開發環境下，即時預覽修改完的 UI 畫面，不用透過模擬器／實機執行才知道
