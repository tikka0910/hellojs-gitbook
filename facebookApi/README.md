# [Facebook Api]

[ 開源的 fb api node module](https://www.npmjs.com/package/fb)

1. 先登入並測試 FB api [連結在這](https://developers.facebook.com/tools/explorer/145634995501895/?method=GET&path=me%2Ffriends&version=v2.7)
2. 右邊有個 Get Token 按鈕
3. Get User Access token
4. 照下方圖片選擇權限
![getToken](https://github.com/FuYaoDe/hellojs-gitbook/blob/master/facebookApi/img/token.png?raw=true)
5. `存取權杖` 會拿到一串亂碼，那就是 token
6. 在下方 `Get ->/2.7/me`
7. 下方就能取得 user id 如下圖
![getId](https://github.com/FuYaoDe/hellojs-gitbook/blob/master/facebookApi/img/id.png?raw=true)
8. 修改GET的路徑`me/friends?fields=id,name`，按下```ENTER```
![getFriends](https://github.com/zzpengg/hellojs-gitbook/blob/master/facebookApi/img/friend.png?raw=true)
9. 把取得方式`GET`=>`POST`
10. 修改路徑`me/feed`
11. 按下`add a field`
12. Name填入`message`，Value填入`要貼文的訊息`
![Post](https://github.com/zzpengg/hellojs-gitbook/blob/master/facebookApi/img/post.png?raw=true)
