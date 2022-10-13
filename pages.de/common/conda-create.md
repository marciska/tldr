# conda create

> Erstellen von neuen Conda Umgebungen.
> Mehr Informationen: <https://docs.conda.io/projects/conda/en/latest/commands/create.html>.

- Erstelle eine neue Umgebung mit dem Namen `py39`, und installiere Python 3.9 und NumPy v1.11 (oder höher) in ihr:

`conda create --yes --name {{py39}} python={{3.9}} "{{numpy>=1.11}}"`

- Erstelle eine exakte Kopie einer Umgebung:

`conda create --clone {{py39}} --name {{py39-copy}}`

- Erstelle eine neue Umgebung mit gegebenem Namen und den zu installierenden Paketen:

`conda create --name {{env_name}} {{package_name}}`
