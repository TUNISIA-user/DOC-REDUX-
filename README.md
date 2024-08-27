# DOC-REDUX-
this map.  how learn redux  and more inforamtion 🔥
# exmple reducer function √ 

const Data= {
  
  counter :  0 ,
  user : null
}
const reducer = (state=Data,action)=>{
  switch(action.type){
    
    case 'ADD_TO_COUNT':
  return {
    ...Data, // this 3 points for save f
    // the data when i get copy of my objecy 
    // if i dont do this 3 points this
    // will be return just {counter:1} and lose my user 
    
    counter :state.counter+1 
  }
  
}
}

action = {
  
  type:'ADD_TO_COUNT' // this Handel with action docyou wannt 
}


console.log(reducer(Data,action))

