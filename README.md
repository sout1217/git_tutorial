# π μ½κΈ°μ 
1. {xxx} λ argument μλλ€
2. [xxx] λ μλ΅ κ°λ₯ argument μλλ€

<br>

## π κΉ κΈ°λ³Έ νλμ λ³΄κΈ°

<br>

![img](img/000.png)

<br>

![git-flow](https://img1.daumcdn.net/thumb/R1280x0.fpng/?fname=http://t1.daumcdn.net/brunch/service/user/3K6t/image/_630fSrZQJj7XdswACSoCGDI1vE.png)

<br>

![img](img/000-1.png)

<br>

![img](img/000-2.png)

<br>

![img](img/000-3.png)

<br>

![img](img/000-4.png)

<br>

![img](img/000-5.png)

<br>

![img](img/000-6.png)

<br>

![img](img/000-7.png)

<br>

## π κΉ κ΄λ¦¬ μμ­
`working directory > stage > local repository > remote repository`

`μμ λλ ν λ¦¬ > μ€νμ΄μ§ > λ‘μ»¬ μ μ₯μ > μκ²© μ μ₯μ`

<br>  

##  π κΉ λ²μ  λ³΄κΈ°
`git --version`

<br>

## π κΉ Bash μ°½ λ΄μ© μ§μ°κΈ°
`clear` or `ctrl + l`  

<br>

## π κΉ μ½ν½ μ€μ  νκΈ°
`git config --global user.name "μ΄λ¦"`  
`git config --global user.email "μ΄λ©μΌ"`  
`git config --global color.ui auto`

<br>

## π κΉ μ½ν½ μ€μ  λ³΄κΈ°
`git config -l`

<br>

## π λλ ν λ¦¬ μμ±
`mkdir νμΌλͺ`

<br>

## π λλ ν λ¦¬ λ³΄κΈ°
`ls` : νμΌ λ³΄κΈ° (.git λλ ν λ¦¬ μλ³΄μ)

`ls -a` : λͺ¨λ  νμΌ λ³΄κΈ°

<br>

## π κΉ μμ νκΈ°
`git init`

<br>

## π κΉ μ κ±° νκΈ°
`rm -rf .git`

`rm -rf {νμΌ λλ λλ ν λ¦¬}` : λ¬»μ§ μκ³  λ°λ‘ μ κ±°

<br>

## π νμΌ μμ± νκΈ°
`touch {νμΌλͺ}`

 ex) `touch index.html`


<br>

## π κΉ νμ¬ μν λ³΄κΈ°
`git status` : branch, untracked,  new file, modified, deleted λ± μ λ³΄λ₯Ό μ μ μλ€


`branch` : λΈλμΉ μ λ³΄  
`untracked` : `working directory` μ μλ νμΌ (ν λ²λ `add` κ° λμ§ μμ νμΌ)  
`new file` : `working directory` μμ `add` λ₯Ό ν΅ν `stage` λ‘ λμ΄μ¨ νμΌ  
`modified` : ν λ² `commit` λκ³  λμ μμ  λ κ²½μ°  
`deleted` : `stage` λλ `local repository` μμ μ­μ λ κ²½μ°


<br>

## π κΉ μΆκ°νκΈ° <small>working directory -> stage</small>
`git add {νμΌλͺ}` : `working directory` μ ν΄λΉ νμΌμ `stage` μ μ΄λ

`git add .` : νμ¬ λλ ν λ¦¬μ `working directory` μ νμΌμ λͺ¨λ `stage` μ μ΄λ

`git add -A` or `git add --all` : `working directory` μ νμΌμ λͺ¨λ `stage` μ μ΄λ

<br>

## π κΉ μ»€λ°νκΈ° <small>stage -> local repository</small>
`git commit -m "{λ©μμ§}"`

<br>

![img](./img/001.png)

`create mode` : νμΌμ΄ `local repository` μμ± λ¨μ μλ¦¬λ λ‘κ·Έ

<br>

## π κΉ λ‘κ·Έ λ³΄κΈ°
`git log`

<br>

![img](./img/002.png)

`commit a0ac7dfc1848b31e96878812df17661b2b7d74a2`  
: μ»€λ° ν΄μ (μ£Όμλ²μ§) - λμ€μ λμκ° λ μ»€λ°ν΄μλ₯Ό ν΅ν΄μ ν©λλ€

`Author: hbh <sout1217@naver.com>`  
: μμμ μμ±ν `git config --global user.name κ³Ό user.email`  λ΄μ©μΌλ‘ μμ± λ©λλ€

`init commit`  
: `git commit -m {λ©μμ§}` μ»€λ° λ©μμ§ λ΄μ©μλλ€

<br>

## π κΉ λ³΄κΈ°
`git show {μ»€λ°ν΄μ}`

<br>

![img](./img/003.png)

> TIP : λ΄μ©μ΄ κΈ΄ κ²½μ° μν°λ₯Ό μ³μ νμ₯μ΄ κ°λ₯νλ©°, λ μ΄μ μλ³΄λ €λ©΄ q λ₯Ό λλ₯΄λ©΄ λΉ μ Έλμ΅λλ€

<br>

## π  νμΌ νΈμ§νκΈ°
`vi {νμΌλͺ}` : νμΌ μλν° μ€ν

<br>

> TIP : vi λ₯Ό μλ ₯ ν `shift + tab` μ λλ₯΄μλ©΄ νμΌ λͺ©λ‘μ΄ λνλ©λλ€

![img](./img/004.gif)

<br>

`i` : μμ±λͺ¨λ  
`esc` : λͺλ Ήλͺ¨λ  
`[λͺλ ΄λͺ¨λ] :wq!` : μ μ₯νκ³  νμΌ λ«κΈ°   
`[λͺλ ΄λͺ¨λ] :q!` : μ μ₯νμ§ μκ³  νμΌ λ«κΈ° 

<br>

## π νμΌ λ΄μ© λ³΄κΈ°
`cat {νμΌλͺ}` : νμΌ λ΄μ© λ³΄κΈ°

<br>

![img](./img/005.png)


<br>

## π μ΄μ  μ»€λ°κ³Ό λ€λ₯Έ μ  λΉκ΅νκΈ°
`git diff`

<br>

![img](./img/006.png)

<br>
 
 `+console.log('Hello Git')` : + λ΄μ©μ΄ μΆκ° λ¨
 `-console.log('Hello Git')` : - λ΄μ©μ΄ μ­μ  λ¨

<br>

## π μ΅κ·Όμ μ»€λ°λ λ©μμ§ λ΄μ© μμ νκΈ°
`git commit --amend [-m] "{λ©μμ§}"`

<br>

![img](./img/007.png)

<br>

`git log` λ₯Ό μ΄μ©νμ¬ λ©μμ§ λ΄μ©μ΄ λ³κ²½λ κ²μ νμΈνλ€

![img](./img/008.png)

<br>

## π κΉ νλΈ(Git-Hub)μ νλ‘μ νΈ μλ‘λνκΈ° μ€μ  <small>(local repository -> remote repository)</small>
- κΉ νλΈ κ³μ μ΄ μμ΄μΌ κ°λ₯ν©λλ€
- κΉ νλΈμμ remote repository μμ±μ μλ΅ν©λλ€ (λ³΄ν΅ local repository μμ remote repository λ‘ μλ‘λ ν©λλ€)

`git remote add origin {κΉνμ£Όμ}`  
ex) `git remote add origin https://github.com/sout1217/sample.git`

<br>

`git push -u -origin {λ§μ€ν°λͺ}` : μ μμ `git remote add` λ‘ μ°κ²°ν `remote repository` μ νμΌμ μλ‘λ ν©λλ€

> TIP : remote repository μ push νκΈ° μν΄μλ `git-hub>SSH and GPG keys>SSH keys>generating SSH keys>Generating a new SSH key and adding it to the ssh-agent>Windows ` μμ μΈμ¦μ λ°μμΌ ν©λλ€  
>
> `ssh-keygen -t ed25519 -C "{μ΄λ©μΌ}"` λΉλ°λ²νΈλ μμ±μν΄λ κ°λ₯ν©λλ€   
> `eval "$(ssh-agent -s)"`  
> `vi ~/.ssh/config`
> `Host * AddKeysToAgent yes UseKeychain yes IdentityFile ~/.ssh/id_ed25519`  
> `ssh-add -K ~/.ssh/id_ed25519`
> `cat ~/.ssh/id_ed25519.pub` : λμ€λ ν€λ₯Ό λ³΅μ¬ `pbcopy < ~/.ssh/id_ed25519.pub` λ‘ λ³΅μ¬ κ°λ₯
> `git hub > New SSH key` ν΄λ¦­ ν `id_ed25519.pub` ν€λ₯Ό λΆμ¬λ£κΈ°

![img](img/009.png)

<br> 

## π κΉ λ§μ€ν° λΈλμΉλͺ λ³κ²½ λ° λΈλμΉ λ¦¬μ€νΈ μ‘°ννκΈ°
`git branch -M {λ§μ€ν°λͺ}` : λ§μ€ν°λͺμ λ°κΏλλ€

`git branch` : νμ¬ μ‘΄μ¬νλ λΈλμΉ λͺ©λ‘λ€μ λ³΄μ¬μ€λλ€ 

![img](img/010.png)

<br>

## π κΉ νλΈ(Git Hub)μ μλ‘λ
`git push [-u origin {λ§μ€ν°λͺ}]` : remote repository μ μ°κ²°μ΄ λμΌ κ°λ₯ν©λλ€

<br>

## π κΉ νλΈ(Git Hub) μ½λ λ€μ΄λ‘λ
`git pull`

> TIP : `git pull` μ `git fetch + git merge` κ°λμ΄λΌκ³  λ³΄λ©΄ λλ€

<br>

## π λΈλμΉ κ΄λ¦¬
![img](img/011.png)

`git branch` : λ‘μ»¬ μ μ₯μ λΈλμΉ λͺ©λ‘ λ³΄κΈ°

`git branch -r` : μκ²© μ μ₯μ λΈλμΉ λͺ©λ‘ λ³΄κΈ°

`git branch -a` : λ‘μ»¬ μ μ₯μ, μκ²© μ μ₯μ λΈλμΉ λͺ©λ‘ λ³΄κΈ°

<br>

## π λΈλμΉ λ§λ€κΈ°
`git branch {λΈλμΉλͺ}`  
ex) `git branch feature-a`

> TIP : νμ¬ λΈλμΉκ° κ°μ§κ³  μλ νμΌλ‘ μλ‘μ΄ λΈλμΉλ₯Ό μμ±ν©λλ€

- master λΈλμΉλ a,b,c νμΌμ κ°κ³  μμΌλ©°,
- develop λΈλμΉλ a, b, c , d νμΌμ κ°κ³  μμΌλ©°,
- feature λΈλμΉλ  a, b, c, d, e νμΌμ κ°κ³  μλ€κ³  κ°μ νλ€λ©΄
- master λΈλμΉμμ μλ‘μ΄ λΈλμΉλ₯Ό μμ±νλ©΄ a,b,c λ₯Ό κ°κ³ ,
- feature λΈλμΉμμ μλ‘μ΄ λΈλ μΉλ₯Ό μμ±νλ©΄ a, b, c, d, e νμΌμ κ°κ³  μλλ€


<br>
 
## π λ€λ₯Έ λΈλμΉλ‘ λ³κ²½νκΈ°
`git checkout {λΈλμΉλͺ}` : ν΄λΉ λΈλμΉλ‘ λ³κ²½ν©λλ€

`git checkout -` : μ΄μ  λΈλμΉλ‘ λ³κ²½ν©λλ€

`git checkout {λΈλμΉλͺ} -f` : ν΄λΉ λΈλμΉλ‘ λ³κ²½νκ³ , νμΌμ λ?μ΄μμλλ€

<br>

## π μμ±ν λΈλμΉμμ μκ²© μ μ₯μμ μλ‘λνκΈ° (something branch local repository -> remote repository)
`git push -u origin {ν΄λΉ λΈλμΉλͺ}` or `git push --set-upstream origin {λΈλμΉλͺ}`  
ex) `git push -u origin feature-a`

<br>

## π λΈλμΉλ₯Ό μμ±νλ©΄μ λΈλμΉ λ³κ²½νκΈ°
`git checkout -b {λΈλμΉλͺ}`
 
<br>

## π λΈλμΉ μ­μ νκΈ°
`git branch -d {λΈλμΉλͺ}`

> TIP : λΈλμΉλ μ­μ λμ§λ§, λ€μ λκ°μ λΈλμΉ λͺμΌλ‘ μμ±νλ©΄ commit μ΄ λ¨μμμ΅λλ€


## π 2κ°μ λΈλμΉ λ³ν©νκΈ°
`git checkout {λ³ν©λ  λΈλμΉλͺ}`  
`git merge {λ³ν©ν  λΈλμΉλͺ}` 

<br>

## π Pull Request (Merging Pull Request)
λ κ°λ₯Ό λ³ν©ν  λλ`pr(pull request)`  μ ν΅ν΄ μννλ κ²μ΄ κ°μ₯ μ’μ΅λλ€  
`pr(pull request)` λ₯Ό ν  κ²½μ° `μκ²© μ μ₯μ(remote repository) - pull requests` ν­μ μμ²­ κΈ°λ‘μ΄ μμ΄λ©°, μμ²­μ νκ°νλ©΄ 
κ·Έ λ 2κ°μ λΈλμΉκ° `λ³ν©(merge)` λ©λλ€

<br>

## π λ‘μ»¬κ³Ό μκ²© λ‘κ·Έ ν μ€λ‘ λ³΄κΈ°
`git log --oneline`

<br>

## π κΉ μν¬ νλ‘μ°
`remote repository` μ `master branch` μ `HEAD commit (μ΅μ  μ»€λ°)` μ `git pull` ν ν

μλ‘μ΄ `branch` λ₯Ό νλ λ§λ€μ΄ μμμ μ§ν ν©λλ€

μμμ μ§ννκΈ° μμ λͺ¨λ  `local commit` μ λ¨Όμ  `sqush(μ€μΏΌμ)` λ₯Ό ν ν μμνλ κ²μ κΆν©λλ€

κ·Έ μ΄μ λ `local repository` λ₯Ό `rebase` λ₯Ό ν  λ `conflict (μΆ©λ)` μ΄ λ°μνκΈ° λλ¬Έμλλ€

`master branch` λ₯Ό `rebase` νμ¬ `commit` μ `sqush` ν©λλ€

<br>

`commit` μ νμ§μκ³  μμ μ μ₯νκΈ° μν΄μλ `stash` λ₯Ό μ΄μ©ν©λλ€

<br>

![img](./img/012.png)

<br>

## π λ³ν© μΆ©λ (Merge Conflict)

> μλλ¦¬μ€  
> aλ local repository μμ μμν commit λ€μ remote repository μ push νλ €κ³  νλ€  
> remote repository λ a μ commit κ³Ό λ¬λΌμ§ κ²μ΄ λ§λ€  
> a λ remote repository μμ push λ₯Ό νμ λ€λ₯Έ λ΄μ©μ΄ μ‘΄μ¬νκΈ° λλ¬Έμ push λ₯Ό κ±°λΆ νλ€    
> a λ remote repository git pull μ νλλ conflict (μΆ©λ) μ΄ λλ©΄μ merging conflict(λ³ν© μΆ©λ)μ΄ λ°μνλ€

![img](./img/013.png)

μ μ΄λ―Έμ§μμ

λ = `local repository` μμλ `<p>This is a another paragraph.</p>` λ‘ λ μμ§λ§

μΈλΆ = `remote repository` μμλ `&lt;h1>This is a Heading&lt;h1> <p>This is a another paragraph.</p>`

μΌλ‘ λμ΄ μμ΄ μλ‘ μΆ©λμ΄ λ°μνμ¬ μλμΌλ‘ μ λ°μμΌλ‘ μμ±μ΄ λ©λλ€

`<<<<<<< HEAD` λ νμ¬ `local repository` μ `HEAD` λ₯Ό λ§ν©λλ€

`>>>>>>> ae128791635b.....ff88` μ `remote repository` μ μ»€λ°ν΄μλ₯Ό κ°λ₯΄μΌμ€λ€

<br>

## π λ¦¬λ² μ΄μ€ (rebase) : μνλ μ§μ (μ»€λ°)μ λ΄μ©μ μμ νκ±°λ μΆκ°νκ³ μ ν  λ
`git pull -r origin {κ°μ Έμ¬ λΈλμΉλͺ}`

μκ²© μ μ₯μμ λ΄μ©μ rebase νμ¬ κ°μ Έμ΅λλ€

μΆκ°νκ±°λ λ³κ²½νκ³ μ ν  λμλ stage μ μ΄λν΄μΌ νκΈ° λλ¬Έμ git add . λ₯Ό ν΄μ€λλ€

`git add .`

λ μ΄μ μμ ν  λ΄μ©μ΄ μλ κ²½μ° commit μ΄ μλ `rebase --continu` λ₯Ό μ΄μ©ν©λλ€

`git rebase --continue`

<br>

`rebase --continue` λ₯Ό ν΄μ λ `conflict` κ° λ°μνλ€λ©΄ ν΄λΉ νμΌμ λ€μ μμ  ν

λ€μ ν λ² `git rebase --continue` λ₯Ό νλ©΄ λ©λλ€

<br>

## π κ°μ  μκ²© μ μ₯μ μλ‘λ
`git push -f`

νμ¬ κ°μ§κ³  μλ `local repository` μ `commit` λ€λ‘ κ΅μ²΄ λ©λλ€

μ¦, `remote repository` μ `commit` λ€μ λ λΌκ°κ³  `local repository`  μ `commit` μΌλ‘ λ³κ²½λ©λλ€ 

μμμ rebase λ₯Ό νμ¬ `remote repository` μ λͺ¨λ  `commit` λ΄μ©λ€μ λ΄ `local repository` λ‘ κ°μ Έμ 

`merging conflict (μΆ©λ λ³ν©)` νλ€λ©΄, κ°μ λ‘ `pust` ν΄λ λ©λλ€

<br>

## π stage μμ working directory λ‘ λ¦¬μ(μ΄λ)
`git reset HEAD` or `git reset --mixed HEAD`

<br>

`git reset HEAD {νμΌλͺ}` : νΉμ  νμΌλ§ λ¦¬μ(μ΄λ) - μ΅μ΄ 1λ² μ΄μμ μ»€λ°μ΄ λμΌ νλ€

<br>

## π woring directory μμ local repository μ commit
`git commit -am "{μ»€λ° λ©μμ§}"`

- ν΄λΉ νμΌμ΄ 1λ² μ΄λΌλ commit λ μ μ΄ μλ€λ©΄ Working Directory μμ Local Repository λ‘ λ°λ‘ commit μ΄ κ°λ₯νλ€
- λ λ²μ§Έ λ°©λ²μ μ²« λ²μ§Έ λ°©λ²κ³Ό vi νΈμ§μ°½μΌλ‘ λμ΄κ°μ§ μκ³  λ°λ‘ μ»€λ°λλ€

<br>

## π local repository μμ stage λ‘ λ¦¬μ(μ΄λ)
`git reset --soft HEAD`

<br>

## π νΉμ  μ§μ  commit μΌλ‘ λ¦¬μ(μ΄λ)
`git reset --hard {μ»€λ°ν΄μ}`

<br>

## π νΉμ  μ»€λ°μ λ΄μ© λ²λ¦¬κΈ°
`git revert {μ»€λ°ν΄μ}`

> TIP :
> 3. μλμ£Όμ HEAD~3  
> 4. μ λμ£Όμ commit1..commit2 

<br>

## π κΉ λͺ¨λ  λ‘κ·Έ
`git reflog`

reset, revert λ± λͺ¨λ  λ‘κ·Έλ₯Ό νμΈν  μ μμΌλ©°, ν΄λΉ μ£Όμλ₯Ό ν΅ν΄ λμκ° μ μλ€

<br>

## π λ‘€λ°± rollback (ItenlliJ μ μ©)
`git reset --mixed [HEAD]` 

`git reset --hard [HEAD]` 

<br>

## π stage, repository μ­μ λ νμΌ λ³΅κ΅¬
`git restore {νμΌλͺ}`

<br>

## π stage -> working directory 
`git restore --staged {νμΌλͺ} `

ν΄λΉ νμΌμ `working directory` μμ μ‘΄μ¬νλ€

<br>

## π μ¨κΈ°κΈ° stash
`git stash save [νμΌλͺ]` : stage μ νμΌλ€μ stack κ³΅κ°μ μμ μ μ₯νλ€

`git stash apply [stash μ΄λ¦]` : κ°μ₯ μ΅κ·Όμ stash μ μλ ₯ λ λ΄μ©λ€μ κ°μ§κ³  μ¨λ€

`git stash drop [stash μ΄λ¦]` : κ°μ₯ μ΅κ·Όμ stash λ΄μ©μ μ κ±°νλ€

`git stash pop` : κ°μ₯ μ΅κ·Ό λ΄μ©μ κ°μ Έμ€λ©΄μ stash μμ μ κ±°νλ€ (apply + drop)

`git stash show -p [[stash μ΄λ¦] | git apply -R` : stash λλλ¦¬κΈ°

<br>

## π μ²΄λ¦¬ ν½
`git cherry-pick` : μ²΄λ¦¬ν½ μ»€λ°μ λ€λ₯Έ λΈλμΉλ₯Ό λ΄κ° μμν λΈλμΉλ‘ ν©μΉλ μ»€λ°
