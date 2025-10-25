# asirem

Asirem Tifinagh Font is a modern, open-source typeface that brings the elegance and heritage of the Tifinagh script into the digital age. Designed for clarity, versatility, and cultural authenticity, Asirem enables seamless typing in Tamazight across platforms such as Linux, Windows, and macOS. 

Its compatibility with most modern applications ensures that Amazigh speakers, educators, and learners can easily write, communicate, and share their language online. By blending tradition with technology, Asirem empowers digital expression while preserving the cultural identity of the Amazigh people.

More than just a font, Asirem is a bridge between heritage and innovation. It supports IRCAM Neo-Tifinagh and extended Tifinagh characters, including Tuareg variations within the Unicode range (U+2D30–U+2D7F). The font’s clean and readable design makes it ideal for both educational and professional use, fostering accessibility and creativity in Amazigh digital spaces. Free and open-source, Asirem stands as a symbol of linguistic pride and cultural continuity, dedicated to keeping the Amazigh language vibrant and visible in the global digital landscape.

<img width="473" height="392" alt="example" src="https://github.com/user-attachments/assets/d8672e68-608a-4044-9030-7735626a317d" />

## Build from SRC

**🛠️ Requirements**

You’ll need FontForge, a free and open-source font editor.

**Install FontForge**

- Run the following command in your terminal:

```
sudo apt update
```
then

```
sudo apt install fontforge
```

- Verify the installation:
```
fontforge -version
```
You should see output showing the installed version of FontForge.

- Assuming your source file is named **asirem.sfd** and is located in the current directory **sources/**
Run:
```
fontforge -lang=ff -c 'Open("asirem.sfd"); Generate("asirem.ttf");'
```
After running this command, you should see a new file named: **asirem.ttf** in the same directory as your source.


## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://openfontlicense.org/open-font-license-official-text/

## About Author

- A. Victor (victoru22@proton.me)

