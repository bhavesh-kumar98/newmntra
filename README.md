this is project of my clone of https://github.com/bhavesh-kumar98/trymn.git
main project " trymn " working good.
but in this ve change something 
like: 
dir js to "scripts"
in index.html we change path  "./xyz" to "/abx/xyz/" of js and image 
but we do in 3-4 commit



1st commit without any change
  -this commit work
 
2st commit we change  in js to scripts and update path of js
  -this commit work 

3st commit we change  in "script" path using absolute path scr="./scripts/slide.js" to src="/scripts/slide.js"
  -not work bcz "https://bhavesh-kumar98.github.io/newmntra/
  my link 
  
  but when use relative path then its work as ./script/...
  https://bhavesh-kumar98.github.io/newmntra/scripts/.....

  but when use absolute path then its NOT work(bcz of root dir) as 
  /script/...
  https://bhavesh-kumar98.github.io/scripts/.....

4st commit we change now add in head<base href="https://bhavesh-kumar98.github.io/newmntra/">

and remove slash from src =/scrpt to src ="scripts/...

5st commit we change 
6st commit we change 
