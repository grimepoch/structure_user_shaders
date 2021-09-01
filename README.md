<h1>Welcome to the STRUCTURE user shader repository for users to share their shader collections!</h1>

Remember that we have a website for developing and testing your shaders:

http://glsl.erogenous-tones.com

<br>
user_shaders/<br>
&nbsp;&nbsp;   gen/<br>
&nbsp;&nbsp;&nbsp;&nbsp;      some_shader.glsl<br>
&nbsp;&nbsp;&nbsp;&nbsp;      user_name/<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         your_shader.glsl<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         your_shader2.glsl<br>
&nbsp;&nbsp;   efx/<br>
templates/shader.glsl
<br>

This is all a work in progress, so for now, here is the thoughts with this:

There is a separate directory for two node types right now; gen & efx.  If you are developing more node shaders
or other types, let me know and I can add them (or you can add them) use the same name as on the SD card.

You can put files in the main shader directory, like user_shaders/gen, or, create a subdirectory under that with a
three letter acronym or name, if you want to keep yours organized.  

If you base your shader (or convert a shader) from a source, please put a link to where you got it in the file as a 
comment in your shader, see the template where I put a reference comment, we always want to attribute where things came from.

By default we won't include these in the STRUCTURE library unless you indicate you'd like them to be added.  To do so,
you can create an Issue on this repo and list out what you want included and we'll take a look.  We will have a file at the root 
called

./included_in_structure.txt

Where I will document what I have added (and close the issue you opened).

BE SURE TO HAVE 3 FPARAMS defined so your shader responds to modulations.  If you don't add them, but it is a cool shader, we might then add them.

Some people like to add three letters to the front of their shader so it will not conflict with other shaders, or let people know who created it, like:

RCB_MyCoolShader.glsl

That helps you find them quicker in STRUCTURE as well.

For now, I think I need to give individual permission to the repo for commiting shaders, create an issue if you have problems or hit us up in the support group and we'll get this process refined.

Looking forward to seeing what this turns into!

-Rick & James
