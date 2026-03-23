# next_js_revision


date --- 23rd March , 2026

lab-19 conclusions--
1) Next.js has file based routing system , defualt port number will be 3000

2) Next.js has /app in which each folder is treated as a route 

3) public contains static assets like -- images,icons,favicons that are fine to share with oublic 

4) package.json contains the scripts and dependencies 

5) layout.tsx wraps all the pages 


6) jsx returns one parent element 

7) components must start with capital letter 

8) export default makes the component usable 


9) a note on project structure ----
    
    1) app/ directory 
        it is the core of next.js router
        handles routing 
        each folder represents a route 

    2) page.tsx
        it is the mandatory file in each route folder 
        it contains UI of a route 

    3) layout.tsx
        it contains the shared UI elements 
        it is used for footers , navbar , etc 

    4) public/
        it contains the static assets which can be directly accessed by public API 
        it contains images, favicons , icons etc 

    5) global.css
        it contains the global styling 
    
    6) node_modules/
        it contains the installed dependencies 
    
    7) package.json
        contains the project metadata
        includes script like --
            npm run dev 
            npm run build 
    
    8) next.config.js 
        contains the configuraitons for next.js 
    
    9) ts.config.json 
        contains the configuration for Typescript 


10) nutshell of imp features --
    file-based routing 
    server side rendering (SSR)
    static site generation(SSG)
    API routes 
    Fast Performance 
    
