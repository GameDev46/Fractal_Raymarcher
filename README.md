<a href="https://github.com/GameDev46" title="Go to GitHub repo">
    <img src="https://img.shields.io/static/v1?label=GameDev46&message=|&color=Green&logo=github&style=for-the-badge&labelColor=1f1f22" alt="GameDev46 - Fractal_Raymarcher">
    <img src="https://img.shields.io/badge/Version-0.7.2-green?style=for-the-badge&labelColor=1f1f22&color=Green" alt="GameDev46 - Fractal_Raymarcher">
</a>


![Static Badge](https://img.shields.io/badge/--1f1f22?style=for-the-badge&logo=HTML5)
![Static Badge](https://img.shields.io/badge/--1f1f22?style=for-the-badge&logo=CSS&logoColor=6060ef)
![Static Badge](https://img.shields.io/badge/--1f1f22?style=for-the-badge&logo=JavaScript)
    
<a href="https://github.com/GameDev46/Fractal_Raymarcher/stargazers">
    <img src="https://img.shields.io/github/stars/GameDev46/Fractal_Raymarcher?style=for-the-badge&labelColor=1f1f22" alt="stars - Fractal_Raymarcher">
</a>
<a href="https://github.com/GameDev46/Fractal_Raymarcher/forks">
    <img src="https://img.shields.io/github/forks/GameDev46/Fractal_Raymarcher?style=for-the-badge&labelColor=1f1f22" alt="forks - Fractal_Raymarcher">
</a>
<a href="https://github.com/GameDev46/Fractal_Raymarcher/issues">
    <img src="https://img.shields.io/github/issues/GameDev46/Fractal_Raymarcher?style=for-the-badge&labelColor=1f1f22&color=blue"/>
 </a>

<br>

<div align="left">
<a href="https://gamedev46.github.io/Fractal_Raymarcher/">
    <img src="https://img.shields.io/badge/View_site-GH_Pages-2ea44f?style=for-the-badge&labelColor=1f1f22" alt="View site - GH Pages">
</a>
</div>

<br>

# Fractal Raymarcher

A 3D fractal renderer that creates high resolution photorealistic images of your own custom fractals

## How It Works

The program makes use of a technique called [raymarching](https://en.wikipedia.org/wiki/Ray_marching#:~:text=Ray%20marching%20is%20a%20class,some%20function%20at%20each%20step.) to estimate the distances to the 3D fractals and the basic geometric shapes. To represent a physical object in raymarching you need a sign distance function (SDF) that simply return the shortest distance to that object when give any 3D point in space. You can find each scene's SDF in its corresponding shader file (e.g. [shader0.glsl](/shaders/shader0.glsl) contains the SDF of the menger sponge on line 195 in the "sponge" function)

## Screenshots

<p>
    <img src="https://github.com/GameDev46/Fractal_Raymarcher/assets/76485006/9238d230-cc2e-47b4-9e6a-24853324f63c" width="400">
    <img src="https://github.com/GameDev46/Fractal_Raymarcher/assets/76485006/1889d98e-16dd-4b11-a95d-49acf06b7ee9" width="400">
    <img src="https://github.com/GameDev46/Fractal_Raymarcher/assets/76485006/00235a4c-afb0-4ddb-b4da-a2a0e209a3bf" width="400">
    <img src="https://github.com/GameDev46/Fractal_Raymarcher/assets/76485006/03fc2b4e-fbad-4c53-9595-e7e6364bb3ed" width="400">
    <img src="https://github.com/GameDev46/Fractal_Raymarcher/assets/76485006/b58a9650-b98f-4b5c-ac72-5f84c752fcbc" width="400">
    <img src="https://github.com/GameDev46/Fractal_Raymarcher/assets/76485006/a12692f5-dee1-417d-802a-ecca860a6485" width="400">
    <img src="https://github.com/GameDev46/Fractal_Raymarcher/assets/76485006/77f43222-ca7f-446c-8608-ed40ee36f2b8" width="400">
    <img src="https://github.com/GameDev46/Fractal_Raymarcher/assets/76485006/c1cbaa1a-095b-4243-be21-78dd52487fa8" width="400">
</p>
