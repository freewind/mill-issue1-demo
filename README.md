Mill Base Project Demo
======================

Install mill:

```
sudo curl -L -o /usr/local/bin/mill https://github.com/lihaoyi/mill/releases/download/0.1.3/0.1.3 && sudo chmod +x /usr/local/bin/mill
```

Run project:

```
mill demo.test
```

Generate IDEA project:

```
mill mill.scalalib.GenIdeaModule/idea
```
