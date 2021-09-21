# VimIM nature code db for ZFVimIM

用于[ZSaberLv0/ZFVimIM](https://github.com/ZSaberLv0/ZFVimIM)的双拼自然码词库(词库来自: [dongyuwei/vimim-data](https://github.com/dongyuwei/vimim-data))

## 配置

* 云输入

    ```
    let g:ZFVimIM_nature_gitUserEmail='YourEmail'
    let g:ZFVimIM_nature_gitUserName='YourUserName'
    let g:ZFVimIM_nature_gitUserToken='YourGithubAccessToken'
    ```

    或

    ```
    let g:zf_git_user_email='YourEmail'
    let g:zf_git_user_name='YourUserName'
    let g:zf_git_user_token='YourGithubAccessToken'
    ```

	配置完成后，任何修改都会按特定的git用户信息推送至github
	（请确保你拥有相应的推送权限）

## 想要添加自己的词库

更多相关信息请查看[ZSaberLv0/ZFVimIM](https://github.com/ZSaberLv0/ZFVimIM#make-your-own-db)
