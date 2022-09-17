# OpenJam
An open-source alternative of Animal Jams desktop's app.asar 

<img style="text-align: center; border-radius: 5px;" src="https://i.imgur.com/VjVjbUF.png">

## Features 
- Replace one file and it's installed, that's it (same with uninstall)
- 3% of Animal Jam's original size (6mb -> ~3mb)
- Removes Animal Jam's built-in tracking for crashes and errors in the asar (not app itself)

## Packing with NPX
```
git clone https://github.com/SuccubusCorp/OpenJam
npx asar pack OpenJam app.asar
mv app.asar %appdata%\Local\Programs\aj-classic\resources
```

## Replacing ASAR
- Download our packed ASAR <a href="https://github.com/SuccubusCorp/OpenJam/releases/download/v1.0.0/app.asar">here</a>
- Replace your original `app.asar` with ours
