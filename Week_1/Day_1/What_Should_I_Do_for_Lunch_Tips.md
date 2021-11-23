const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false){
    console.log("Not hungry, get back to work and wait until you are hungry.");
  } else if (hungry === true && availableTime <20){
    console.log("Pick something up and eat it in the lab or in the kitchen");
  } else if (hungry === true && (availableTime >=20 && availableTime <=30)); {
    console.log("You deserve a break! Try a place in Gastown");
  } if (hungry === true && availableTime > 30); {
    console.log (" This is a bootcamp, you should probably recondider");
  }
  
}