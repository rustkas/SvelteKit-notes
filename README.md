# SvelteKit Tips and Tricks

Usefull commands. Tip and tricks

## Create new project 
1. Enter project name.
2. Run setup. Answer installer questions.
3. Go to project folder.
3. Intall SvelteKit component

### Linux
`echo "Enter project name" && read project_name && npm create svelte@latest $project_name && cd $project_name && npm i`

### Windows 11

`set "project_name=" && set /p "project_name=Enter project name: " && npm create svelte@latest %project_name% && cd %project_name% && npm i`


## Add Tailwind
1. Install
`npm install -D tailwindcss postcss autoprefixer svelte-preprocess &&  npx tailwindcss init tailwind.config.cjs -p && code . && exit`
2. Project template is here `templates\sveltekit-tailwind`

# Add DaisyUI
1. Install
`npm i daisyui`
2. Project template is here `templates\sveltekit-tailwind-dausyui`
