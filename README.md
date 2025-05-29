# Presentation Resources
This repo hosts materials used for presentations, including slides and diagram files.

# How to Upload New Resources
1. Clone the repository to your local machine.
```bash
   git clone https://github.com/ngcp-project/presentation-resources.git
```
2. **Create a New Folder**: Each team should have its own folder.
3. **Add Your Files**: Place your slides and diagrams in the appropriate folder.
4. Install [Git LFS](https://git-lfs.com/) if you haven't already.
5. Initialize Git LFS in your repository:
```bash
   git lfs install
```
6. **Track Large Files**: If you have large files, track them with Git LFS using the following command below and adjusting for the file types you are using:
```bash
   git lfs track "*.png" "*.jpg" "*.pdf"
```
7. **Commit Your Changes**: Add and commit your changes.
```bash
   git add .
   git commit -m "Add new presentation resources"
```
8. **Push to the Repository**: Push your changes to the remote repository.
```bash
   git push
```