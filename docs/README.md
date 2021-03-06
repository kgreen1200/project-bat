<!--
File:           README.md
Description:    Provides introduction and usage information for the project.
-->

<div id="title_card" align="center">

![GitHub last commit](https://img.shields.io/github/last-commit/kgreen1200/project-bat?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0xNy41IDExLjc1YS43NS43NSAwIDAxLjc1LS43NWg1YS43NS43NSAwIDAxMCAxLjVoLTVhLjc1Ljc1IDAgMDEtLjc1LS43NXptLTE3LjUgMEEuNzUuNzUgMCAwMS43NSAxMWg1YS43NS43NSAwIDAxMCAxLjVoLTVhLjc1Ljc1IDAgMDEtLjc1LS43NXoiLz48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0xMiAxNi4yNWE0LjUgNC41IDAgMTAwLTkgNC41IDQuNSAwIDAwMCA5em0wIDEuNWE2IDYgMCAxMDAtMTIgNiA2IDAgMDAwIDEyeiIvPjwvc3ZnPg==)
![GitHub Discussions](https://img.shields.io/github/discussions/kgreen1200/project-bat?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0xLjUgMi43NWEuMjUuMjUgMCAwMS4yNS0uMjVoOC41YS4yNS4yNSAwIDAxLjI1LjI1djUuNWEuMjUuMjUgMCAwMS0uMjUuMjVoLTMuNWEuNzUuNzUgMCAwMC0uNTMuMjJMMy41IDExLjQ0VjkuMjVhLjc1Ljc1IDAgMDAtLjc1LS43NWgtMWEuMjUuMjUgMCAwMS0uMjUtLjI1di01LjV6TTEuNzUgMUExLjc1IDEuNzUgMCAwMDAgMi43NXY1LjVDMCA5LjIxNi43ODQgMTAgMS43NSAxMEgydjEuNTQzYTEuNDU3IDEuNDU3IDAgMDAyLjQ4NyAxLjAzTDcuMDYxIDEwaDMuMTg5QTEuNzUgMS43NSAwIDAwMTIgOC4yNXYtNS41QTEuNzUgMS43NSAwIDAwMTAuMjUgMWgtOC41ek0xNC41IDQuNzVhLjI1LjI1IDAgMDAtLjI1LS4yNWgtLjVhLjc1Ljc1IDAgMTEwLTEuNWguNWMuOTY2IDAgMS43NS43ODQgMS43NSAxLjc1djUuNUExLjc1IDEuNzUgMCAwMTE0LjI1IDEySDE0djEuNTQzYTEuNDU3IDEuNDU3IDAgMDEtMi40ODcgMS4wM0w5LjIyIDEyLjI4YS43NS43NSAwIDExMS4wNi0xLjA2bDIuMjIgMi4yMnYtMi4xOWEuNzUuNzUgMCAwMS43NS0uNzVoMWEuMjUuMjUgMCAwMC4yNS0uMjV2LTUuNXoiLz48L3N2Zz4=)
![GitHub Repo stars](https://img.shields.io/github/stars/kgreen1200/project-bat?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik04IC4yNWEuNzUuNzUgMCAwMS42NzMuNDE4bDEuODgyIDMuODE1IDQuMjEuNjEyYS43NS43NSAwIDAxLjQxNiAxLjI3OWwtMy4wNDYgMi45Ny43MTkgNC4xOTJhLjc1Ljc1IDAgMDEtMS4wODguNzkxTDggMTIuMzQ3bC0zLjc2NiAxLjk4YS43NS43NSAwIDAxLTEuMDg4LS43OWwuNzItNC4xOTRMLjgxOCA2LjM3NGEuNzUuNzUgMCAwMS40MTYtMS4yOGw0LjIxLS42MTFMNy4zMjcuNjY4QS43NS43NSAwIDAxOCAuMjV6bTAgMi40NDVMNi42MTUgNS41YS43NS43NSAwIDAxLS41NjQuNDFsLTMuMDk3LjQ1IDIuMjQgMi4xODRhLjc1Ljc1IDAgMDEuMjE2LjY2NGwtLjUyOCAzLjA4NCAyLjc2OS0xLjQ1NmEuNzUuNzUgMCAwMS42OTggMGwyLjc3IDEuNDU2LS41My0zLjA4NGEuNzUuNzUgMCAwMS4yMTYtLjY2NGwyLjI0LTIuMTgzLTMuMDk2LS40NWEuNzUuNzUgMCAwMS0uNTY0LS40MUw4IDIuNjk0di4wMDF6Ii8+PC9zdmc+)
![GitHub top language](https://img.shields.io/github/languages/top/kgreen1200/project-bat?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00LjcyIDMuMjJhLjc1Ljc1IDAgMDExLjA2IDEuMDZMMi4wNiA4bDMuNzIgMy43MmEuNzUuNzUgMCAxMS0xLjA2IDEuMDZMLjQ3IDguNTNhLjc1Ljc1IDAgMDEwLTEuMDZsNC4yNS00LjI1em02LjU2IDBhLjc1Ljc1IDAgMTAtMS4wNiAxLjA2TDEzLjk0IDhsLTMuNzIgMy43MmEuNzUuNzUgMCAxMDEuMDYgMS4wNmw0LjI1LTQuMjVhLjc1Ljc1IDAgMDAwLTEuMDZsLTQuMjUtNC4yNXoiLz48L3N2Zz4=)
![GitHub language count](https://img.shields.io/github/languages/count/kgreen1200/project-bat?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0xLjc1IDEuNWEuMjUuMjUgMCAwMC0uMjUuMjV2MTIuNWMwIC4xMzguMTEyLjI1LjI1LjI1aDEyLjVhLjI1LjI1IDAgMDAuMjUtLjI1VjEuNzVhLjI1LjI1IDAgMDAtLjI1LS4yNUgxLjc1ek0wIDEuNzVDMCAuNzg0Ljc4NCAwIDEuNzUgMGgxMi41QzE1LjIxNiAwIDE2IC43ODQgMTYgMS43NXYxMi41QTEuNzUgMS43NSAwIDAxMTQuMjUgMTZIMS43NUExLjc1IDEuNzUgMCAwMTAgMTQuMjVWMS43NXptOS4yMiAzLjcyYS43NS43NSAwIDAwMCAxLjA2TDEwLjY5IDggOS4yMiA5LjQ3YS43NS43NSAwIDEwMS4wNiAxLjA2bDItMmEuNzUuNzUgMCAwMDAtMS4wNmwtMi0yYS43NS43NSAwIDAwLTEuMDYgMHpNNi43OCA2LjUzYS43NS43NSAwIDAwLTEuMDYtMS4wNmwtMiAyYS43NS43NSAwIDAwMCAxLjA2bDIgMmEuNzUuNzUgMCAxMDEuMDYtMS4wNkw1LjMxIDhsMS40Ny0xLjQ3eiIvPjwvc3ZnPg==)

# Project B.A.T.

**A Minecraft Blueprint Automation Tool**

<!--Quick Links-->
[![Issues](https://img.shields.io/badge/-Issues-181717?style=for-the-badge)](https://github.com/kgreen1200/project-bat/issues)
[![Pull Requests](https://img.shields.io/badge/-Pull_Requests-181717?style=for-the-badge)](https://github.com/kgreen1200/project-bat/pulls)
[![Discussions](https://img.shields.io/badge/-Discussions-181717?style=for-the-badge)](https://github.com/kgreen1200/project-bat/discussions)

</div>

<details>
<summary><b>Table of Content</b></summary>

</details>

<a href="#title_card"><img alt="Back To Top" align="right" src="https://img.shields.io/badge/Back_To_Top-181717?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0zLjIyIDkuNzhhLjc1Ljc1IDAgMDEwLTEuMDZsNC4yNS00LjI1YS43NS43NSAwIDAxMS4wNiAwbDQuMjUgNC4yNWEuNzUuNzUgMCAwMS0xLjA2IDEuMDZMOCA2LjA2IDQuMjggOS43OGEuNzUuNzUgMCAwMS0xLjA2IDB6Ii8+PC9zdmc+"></a>

## ???? About Project B.A.T.

<a href="#title_card"><img alt="Back To Top" align="right" src="https://img.shields.io/badge/Back_To_Top-181717?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0zLjIyIDkuNzhhLjc1Ljc1IDAgMDEwLTEuMDZsNC4yNS00LjI1YS43NS43NSAwIDAxMS4wNiAwbDQuMjUgNC4yNWEuNzUuNzUgMCAwMS0xLjA2IDEuMDZMOCA2LjA2IDQuMjggOS43OGEuNzUuNzUgMCAwMS0xLjA2IDB6Ii8+PC9zdmc+"></a>

## ??????? Getting Started

<a href="#title_card"><img alt="Back To Top" align="right" src="https://img.shields.io/badge/Back_To_Top-181717?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0zLjIyIDkuNzhhLjc1Ljc1IDAgMDEwLTEuMDZsNC4yNS00LjI1YS43NS43NSAwIDAxMS4wNiAwbDQuMjUgNC4yNWEuNzUuNzUgMCAwMS0xLjA2IDEuMDZMOCA2LjA2IDQuMjggOS43OGEuNzUuNzUgMCAwMS0xLjA2IDB6Ii8+PC9zdmc+"></a>

## ??????? Project Components

### Built With

![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white&labelColor=171515)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-005ccb?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=2088ff)
![Google Earth](https://img.shields.io/badge/Google_Earth-0059c1?style=for-the-badge&logo=googleearth&logoColor=white&labelColor=4285f4)
![Markdown](https://img.shields.io/badge/Markdown-2c2c2c?style=for-the-badge&logo=markdown&logoColor=white&labelColor=000000)
![Material Design](https://img.shields.io/badge/Material_Design-494949?style=for-the-badge&logo=materialdesign&logoColor=white&labelColor=757575)
![Material Design Icons](https://img.shields.io/badge/Material_Design_Icons-0069c0?style=for-the-badge&logo=materialdesignicons&logoColor=white&labelColor=2196f3)
![Minecraft](https://img.shields.io/badge/Minecraft-005700?style=for-the-badge&logoColor=white&labelColor=3b8526&logo=data:image/svg+xml;base64,PHN2ZyBpZD0iU3ZnanNTdmcxMDAxIiB3aWR0aD0iMjg4IiBoZWlnaHQ9IjI4OCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB2ZXJzaW9uPSIxLjEiIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB4bWxuczpzdmdqcz0iaHR0cDovL3N2Z2pzLmNvbS9zdmdqcyI+PGRlZnMgaWQ9IlN2Z2pzRGVmczEwMDIiPjwvZGVmcz48ZyBpZD0iU3ZnanNHMTAwOCI+PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyODgiIGhlaWdodD0iMjg4IiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwYXRoIGQ9Ik00LDJIMjBDMjEuMSwyIDIyLDIuOSAyMiw0VjIwQzIyLDIxLjEgMjEuMSwyMiAyMCwyMkg0QzIuOSwyMiAyLDIxLjEgMiwyMFY0QzIsMi45IDIuOSwyIDQsMk02LDZWMTBIMTBWMTJIOFYxOEgxMFYxNkgxNFYxOEgxNlYxMkgxNFYxMEgxOFY2SDE0VjEwSDEwVjZINloiIGZpbGw9IiNmZmZmZmYiIGNsYXNzPSJjb2xvcjAwMCBzdmdTaGFwZSI+PC9wYXRoPjwvc3ZnPjwvZz48L3N2Zz4=)
![PyTest](https://img.shields.io/badge/Pytest-0071b1?style=for-the-badge&logo=pytest&logoColor=white&labelColor=009fe3)
![Python](https://img.shields.io/badge/Python-005a8a?style=for-the-badge&logo=python&logoColor=white&labelColor=4887ba)
![Visual Studio Code](https://img.shields.io/badge/Visual_Studio_Code-0081c0?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=48b0f3)
![Windows](https://img.shields.io/badge/Windows-004da4?style=for-the-badge&logo=windows&logoColor=white&labelColor=0078d6)
![Shields.io](https://img.shields.io/badge/Shields.io-2c2c2c?style=for-the-badge&logo=shields.io&logoColor=white&labelColor=000000)
![QT](https://img.shields.io/badge/Qt-009b21?style=for-the-badge&logo=qt&logoColor=white&labelColor=40cd52)
![PyPi](https://img.shields.io/badge/PyPI-00437d?style=for-the-badge&logo=pypi&logoColor=white&labelColor=006dad)
![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-4f8b42?style=for-the-badge&logo=openstreetmap&logoColor=white&labelColor=7ebc6f)
![JavaScript](https://img.shields.io/badge/JavaScript-baaa15?style=for-the-badge&logo=javascript&logoColor=black&labelColor=f0db4f)

### System Architecture

<a href="#title_card"><img alt="Back To Top" align="right" src="https://img.shields.io/badge/Back_To_Top-181717?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0zLjIyIDkuNzhhLjc1Ljc1IDAgMDEwLTEuMDZsNC4yNS00LjI1YS43NS43NSAwIDAxMS4wNiAwbDQuMjUgNC4yNWEuNzUuNzUgMCAwMS0xLjA2IDEuMDZMOCA2LjA2IDQuMjggOS43OGEuNzUuNzUgMCAwMS0xLjA2IDB6Ii8+PC9zdmc+"></a>

## ???? Roadmap

<a href="#title_card"><img alt="Back To Top" align="right" src="https://img.shields.io/badge/Back_To_Top-181717?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0zLjIyIDkuNzhhLjc1Ljc1IDAgMDEwLTEuMDZsNC4yNS00LjI1YS43NS43NSAwIDAxMS4wNiAwbDQuMjUgNC4yNWEuNzUuNzUgMCAwMS0xLjA2IDEuMDZMOCA2LjA2IDQuMjggOS43OGEuNzUuNzUgMCAwMS0xLjA2IDB6Ii8+PC9zdmc+"></a>

## ?????? Author

Kevin Green | [kgreen1200](https://github.com/kgreen1200)

<a href="#title_card"><img alt="Back To Top" align="right" src="https://img.shields.io/badge/Back_To_Top-181717?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0zLjIyIDkuNzhhLjc1Ljc1IDAgMDEwLTEuMDZsNC4yNS00LjI1YS43NS43NSAwIDAxMS4wNiAwbDQuMjUgNC4yNWEuNzUuNzUgMCAwMS0xLjA2IDEuMDZMOCA2LjA2IDQuMjggOS43OGEuNzUuNzUgMCAwMS0xLjA2IDB6Ii8+PC9zdmc+"></a>

## ???? Acknowledgements

<a href="#title_card"><img alt="Back To Top" align="right" src="https://img.shields.io/badge/Back_To_Top-181717?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0zLjIyIDkuNzhhLjc1Ljc1IDAgMDEwLTEuMDZsNC4yNS00LjI1YS43NS43NSAwIDAxMS4wNiAwbDQuMjUgNC4yNWEuNzUuNzUgMCAwMS0xLjA2IDEuMDZMOCA2LjA2IDQuMjggOS43OGEuNzUuNzUgMCAwMS0xLjA2IDB6Ii8+PC9zdmc+"></a>

## ?????? License

![GitHub license](https://img.shields.io/github/license/kgreen1200/project-bat?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik04Ljc1Ljc1YS43NS43NSAwIDAwLTEuNSAwVjJoLS45ODRjLS4zMDUgMC0uNjA0LjA4LS44NjkuMjNsLTEuMjg4LjczN0EuMjUuMjUgMCAwMTMuOTg0IDNIMS43NWEuNzUuNzUgMCAwMDAgMS41aC40MjhMLjA2NiA5LjE5MmEuNzUuNzUgMCAwMC4xNTQuODM4bC41My0uNTMtLjUzLjUzdi4wMDFsLjAwMi4wMDIuMDAyLjAwMi4wMDYuMDA2LjAxNi4wMTUuMDQ1LjA0YTMuNTE0IDMuNTE0IDAgMDAuNjg2LjQ1QTQuNDkyIDQuNDkyIDAgMDAzIDExYy44OCAwIDEuNTU2LS4yMiAyLjAyMy0uNDU0YTMuNTE1IDMuNTE1IDAgMDAuNjg2LS40NWwuMDQ1LS4wNC4wMTYtLjAxNS4wMDYtLjAwNi4wMDItLjAwMi4wMDEtLjAwMkw1LjI1IDkuNWwuNTMuNTNhLjc1Ljc1IDAgMDAuMTU0LS44MzhMMy44MjIgNC41aC4xNjJjLjMwNSAwIC42MDQtLjA4Ljg2OS0uMjNsMS4yODktLjczN2EuMjUuMjUgMCAwMS4xMjQtLjAzM2guOTg0VjEzaC0yLjVhLjc1Ljc1IDAgMDAwIDEuNWg2LjVhLjc1Ljc1IDAgMDAwLTEuNWgtMi41VjMuNWguOTg0YS4yNS4yNSAwIDAxLjEyNC4wMzNsMS4yOS43MzZjLjI2NC4xNTIuNTYzLjIzMS44NjguMjMxaC4xNjJsLTIuMTEyIDQuNjkyYS43NS43NSAwIDAwLjE1NC44MzhsLjUzLS41My0uNTMuNTN2LjAwMWwuMDAyLjAwMi4wMDIuMDAyLjAwNi4wMDYuMDE2LjAxNS4wNDUuMDRhMy41MTcgMy41MTcgMCAwMC42ODYuNDVBNC40OTIgNC40OTIgMCAwMDEzIDExYy44OCAwIDEuNTU2LS4yMiAyLjAyMy0uNDU0YTMuNTEyIDMuNTEyIDAgMDAuNjg2LS40NWwuMDQ1LS4wNC4wMS0uMDEuMDA2LS4wMDUuMDA2LS4wMDYuMDAyLS4wMDIuMDAxLS4wMDItLjUyOS0uNTMxLjUzLjUzYS43NS43NSAwIDAwLjE1NC0uODM4TDEzLjgyMyA0LjVoLjQyN2EuNzUuNzUgMCAwMDAtMS41aC0yLjIzNGEuMjUuMjUgMCAwMS0uMTI0LS4wMzNsLTEuMjktLjczNkExLjc1IDEuNzUgMCAwMDkuNzM1IDJIOC43NVYuNzV6TTEuNjk1IDkuMjI3Yy4yODUuMTM1LjcxOC4yNzMgMS4zMDUuMjczczEuMDItLjEzOCAxLjMwNS0uMjczTDMgNi4zMjdsLTEuMzA1IDIuOXptMTAgMGMuMjg1LjEzNS43MTguMjczIDEuMzA1LjI3M3MxLjAyLS4xMzggMS4zMDUtLjI3M0wxMyA2LjMyN2wtMS4zMDUgMi45eiIvPjwvc3ZnPg==)

```text
MIT License

Copyright (c) 2022 Kevin Green

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---
Kevin Green | [kgreen1200](https://github.com/kgreen1200)

<a href="#title_card"><img alt="Back To Top" align="right" src="https://img.shields.io/badge/Back_To_Top-181717?style=for-the-badge&labelColor=181717&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiIgdmlld0JveD0iMCAwIDE2IDE2Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0zLjIyIDkuNzhhLjc1Ljc1IDAgMDEwLTEuMDZsNC4yNS00LjI1YS43NS43NSAwIDAxMS4wNiAwbDQuMjUgNC4yNWEuNzUuNzUgMCAwMS0xLjA2IDEuMDZMOCA2LjA2IDQuMjggOS43OGEuNzUuNzUgMCAwMS0xLjA2IDB6Ii8+PC9zdmc+"></a>
