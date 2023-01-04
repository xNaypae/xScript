# // Config For Load Script Multiple Account \\\ #

# How To Use 

You can push Pang["Config"] on top 
  and push 
  loadstring(game:HttpGet("https://raw.githubusercontent.com/xNaypae/xScript/main/Loaded-Source"))();


### Example ###

Pang["Config"] = {

  {
      Username = "user1", -- Username
      Loader_script = function()
        loadstring(game:HttpGet("test"))();
      end
  }, 
  
  {
      Username = "NayKoki",
      Loader_script = function()
        loadstring(game:HttpGet("test"))();
      end
  }, 
  
  {
      Username = "xGiojox",
      Loader_script = function()
        loadstring(game:HttpGet("test"))();
      end
  }
  
}
