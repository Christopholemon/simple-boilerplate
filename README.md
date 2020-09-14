For really simple web projects, generally hosted locally. It's pretty rough, but should be good enough for coding tests, proof of concepts, or generally screwing around with stuff. This is a cut down version of my bigger project, https://github.com/Christopholemon/js-web-boilerplate. 

Local build is currently using webpack dev server, but running a basic PHP server on the output folder directly works too, eg. __php -S localhost:3000__.

## References/Notes
**Styles:** Using BEMSkel as basis for style structuring https://github.com/karloespiritu/bemskel. Have made some tweaks and adjustments<br />
**React file structure:** Using this as a rough guide, structured towards using React Hooks. Have kept the styles separate, too. https://medium.com/@Charles_Stover/optimal-file-structure-for-react-applications-f3e35ad0a145