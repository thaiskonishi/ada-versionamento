# ada-versionamento

## Site útil

https://www.atlassian.com/git/tutorials/undoing-changes

Comandos:
git log --stat
git log --oneline
git commit --ammend -m"comentario"
git commit --ammend --no-edit
git log --grep="teste"
git checkout nomeArquivo -->sem add, voltarei para o stado anterior.

token github

> settings>developer settings>personal acess tokens>tokens classic >generate new token(classic)

https://stackoverflow.com/questions/2474353/how-to-copy-commits-from-one-branch-to-another
git stash branch <nomebranch> stash{0}

criando tags:

git tag ---> mostra as tags que tem
git tag v1 VERSUS git tag -a -m"descrição da tag" <nome da tag>
git tag -a -m"comentario da tag" v3 --> se não colocar o numero do commit , eu coloco a tag no ultimo commit
git tag -n ---->comastra detalhes das tags que tem
git tag <nome da tag> <numero do commit> --> apontar pra qual commit eu quero colocar uma exemplo: git tag descontinuada 9043d37
git tag -d <nome da tag> --> apaga a tag que coloquei
git push --delete origin descontinuado -->deletando a branch descontinuad
