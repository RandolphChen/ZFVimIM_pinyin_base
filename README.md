# VimIM nature code db for ZFVimIM

[中文用户看这里](https://github.com/RandolphChen/ZFVimIM_vimim-nature/blob/master/README_cn.md)

shuangpin nature code db file from [dongyuwei/vimim-data](https://github.com/dongyuwei/vimim-data)
for [ZSaberLv0/ZFVimIM](https://github.com/ZSaberLv0/ZFVimIM)

## installation

Use [vim-plug](https://github.com/junegunn/vim-plug) to install this db source, 
add the following line to your vimrc

```
Plug 'RandolphChen/ZFVimIM_vimim-nature', {'branch':'origin/release'}
```

## configs

* cloud input

    ```
    let g:ZFVimIM_nature_gitUserEmail='YourEmail'
    let g:ZFVimIM_nature_gitUserName='YourUserName'
    let g:ZFVimIM_nature_gitUserToken='YourGithubAccessToken'
    ```

    or

    ```
    let g:zf_git_user_email='YourEmail'
    let g:zf_git_user_name='YourUserName'
    let g:zf_git_user_token='YourGithubAccessToken'
    ```

    once configured, any changes would be pushed with the specified git user info
    (make sure you have push permission)

## add your own db

refer to [ZSaberLv0/ZFVimIM](https://github.com/ZSaberLv0/ZFVimIM#make-your-own-db)
for more info

