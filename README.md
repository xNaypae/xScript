# // Config For Load Script Multiple Account \\\ #

# How To Use 

You can push Pang["Config"] on top 
and push 
** loadstring(game:HttpGet("https://raw.githubusercontent.com/xNaypae/xScript/main/Loaded-Source"))(); **


### Example ###
**Don't forgot to change loadstring source**
Pang["Config"] = {

  {
      Username = "user1",
      Loader_script = function()
        loadstring(game:HttpGet("test"))();
      end
  }, 
  
  {
      Username = "user2",
      Loader_script = function()
        loadstring(game:HttpGet("test"))();
      end
  }, 
  
  {
      Username = "user3",
      Loader_script = function()
        loadstring(game:HttpGet("test"))();
      end
  }
  
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/xNaypae/xScript/main/Loaded-Source"))();

On File In Autoexec
