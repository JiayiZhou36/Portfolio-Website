# Cloud_Project_1


[![pipeline status](https://gitlab.com/JiayiZhou36/cloud_project_1/badges/main/pipeline.svg)](https://gitlab.com/JiayiZhou36/cloud_project_1/-/commits/main)


### Static Site with Zola
[Portfolio Website](https://jiayizhou.vercel.app/)

### Purpose
This project creates a static site with Zola, a Rust static site generator, that will hold all of the portofolio work in this class.

### Preparation
1. Install Zola 
2. Create website with `zola init`
3. Add a theme for css `cd themes` then `git submodule add <theme name>`
4. Create pages in the `content` folder 
5. `zola serve` to test website or `zola build`
6. Install Vercel CLI 
7. Login to Vercel with `vercel login`
8. Link your repo with `vercel link`
9. Copy your Vercel token, Vercel team id, and Vercel Org id to Gitlab secrets 
10. Push repo to run pipeline filr `.gitlab-ci.yml`
