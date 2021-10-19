*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

body {
    background: rgb(240, 202, 255);
    height: 3000px;
}
/*

header {
    display: flex;
    height: 100px;
    background: rgb(15, 223, 223);
    box-shadow: grey 1px 2px 10px 1px;
    margin: 3px 3px;
}

.container_header {
 
}

.container_header ul a {
    padding: 10px;
    margin: 5px;
    background: rgb(255, 123, 0);
    width: 120px;
    height: 40px;
    line-height: 50px;
    
 

}

.container_header ul a {
    list-style: none;
    text-decoration: none;
    display: inline-block;  
}

.container_header ul a li {
    

}
*/

.header {
    display: flex;
    width: 100%;
    height: 200px;
    background: rgb(191, 163, 255);
    box-shadow: grey 0px 3px 6px 0.9px;
    position: relative;
    
}

.container_header {
    display: flex;
    flex-direction: column;
    flex: content;
}

.container_header ul {
  display: flex;
  flex-wrap: wrap;
  flex: content;
  justify-content: center;
  align-items: flex-end;
  
  
  
}

.container_header ul li {
    display: flex;
    background: rgb(82, 177, 255);
    margin: 0px 1px;
    
    

}

.container_header ul li a {
    display: flex;
    flex: content;
    text-decoration: none;
    list-style: none;
    color: rgb(255, 255, 255);
    width: 120px;
    height: 50px;
    justify-content: center;
    align-items: center; 
    transition: 0.4s;
    box-shadow: grey 0px 3px 4px 0.1px;
}

.container_header ul li a:hover {
    background: rgb(36, 36, 36);
    color: rgb(255, 255, 255);
    border-bottom: rgb(255, 145, 0) 5px solid;
}

#logo_header {
    display: flex;
    width: 200px;
    height: 200px;
    position: relative;
    bottom: 50px;
}

.main {
    display: flex;
    flex: content;
    flex-direction: column;  
    margin-right: 10px;
}

.main div {
    display: flex;
    background: rgb(191, 163, 255);
    box-shadow: grey 0px 3px 6px 0.9px;
    width: 500px;
    height: 300px;
    margin: 15px 5px;
}


