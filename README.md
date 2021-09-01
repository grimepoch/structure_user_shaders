Welcome to the user shader repository for users to share their shader collections!

The directories are separated into different areas based on what you want us to do with the files as well
<br>
user_shaders/<br>
&nbsp;&nbsp;   gen/<br>
&nbsp;&nbsp;&nbsp;&nbsp;      some_shader.glsl<br>
&nbsp;&nbsp;&nbsp;&nbsp;      user_name/<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         your_shader.glsl<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         your_shader2.glsl<br>
&nbsp;&nbsp;   efx/<br>
<br>
Basically the idea is you use your own moniker (user_name) if you want to keep your shaders separate and organized
on the server.  If not, you can place them at the top level of the shader type.

If you base your shader (or convert a shader) from a source, please put a link to where you got it in the file as a 
comment, we always want to attribute where things came from.

By default we won't include these in the STRUCTURE library unless you indicate you'd like them to be added.  To do so,
you can create and Issue and list out what you want included and we'll take a look.  We will have a file at the root 
called

./include_in_structure.txt

Where I will document what I have added (and close the issue you opened)

Some people like to add three letters to the front of their shader so it will not conflict with other shaders, like:

RCB_MyCoolShader.glsl

That helps you find them quicker in STRUCTURE as well.

For now, I think I need to give individual permission to the repo for commiting shaders, create an issue if you have problems.

Looking forward to seeing what this turns into!

-Rick
