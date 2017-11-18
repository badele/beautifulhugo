## Preview features

### french-translation

![french-translation](https://github.com/badele/beautifulhugo/raw/apply_my_branchs/apply_my_branchs/french.png)

### title-image

![itle-image](https://github.com/badele/beautifulhugo/raw/apply_my_branchs/apply_my_branchs/image-title.png)

### highlighting

![highlighting](https://github.com/badele/beautifulhugo/raw/apply_my_branchs/apply_my_branchs/highlighting.png)

### rssfeed

Add customized RSS url feed

### staticman

![staticman](https://github.com/badele/beautifulhugo/raw/apply_my_branchs/apply_my_branchs/staticman.png)

## Apply my branchs

### Get forked repository

```bash
cd blog_destination/themes
git clone git@github.com:badele/beautifulhugo.git
```

### Apply a patchs

```bash
git checkout master
git checkout -b used_by_my_blog 7cdd0e0b3d986af12079c0f37d069fbe2713ab16
git rebase staticman
git rebase post-info
```
