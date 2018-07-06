# gitignore
 A collection of useful .gitignore templates

### Geting started:


### The new github EMAIL Policy & "Push rejected: Push master to origin/master was rejected by remote" 
Account->Setting->Emails:
If Block command line pushes that expose my email is CHECKED than:

On Top of the page you will see somthing like that:
[example@example.com] [Primary Not visible in emails] [Receives notifications]

When you moved you mouse on the [Primary Not visible in emails] you will find your email:
should look like <NUMBER>+<account>@users.noreply.github.com
[123456+abcdef@users.noreply.github.com]


```
git commit --amend --author 'FirstName LastName <123456+abcdef@users.noreply.github.com>' --no-edit
git commit --amend --reset-author
git config user.email 123456+abcdef@users.noreply.github.com
git config --global user.email 123456+abcdef@users.noreply.github.com
```



## Insperation & References:
* https://github.com/github/gitignore
* https://github.com/joeblau/gitignore.io
* 


## License
This repository contains a variety of content; some developed by Limitless Virtue LLC and Shmuel Maruani, and some from third-parties.
The third-party content is distributed under the license provided by those parties.
The content developed by Shmuel Maruani is distributed under MIT License - see the [LICENSE](LICENSE) file for details.

