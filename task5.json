function sort(arr){
  
    
  var tmp;
  for(var i = 0; i < arr.length; i++){
    for(var j = i + 1; j < arr.length; j++){
      /* if ASCII code greater then swap the elements position*/
      if(arr[i] > arr[j]){
        tmp = arr[i];
        arr[i] = arr[j];
        arr[j] = tmp;
      }
    }
  }

  return arr;
}
function mean(arr){
    let sum=0;
    for(let i=0;i<arr.length;i++){
        sum = sum + arr[i];
    } 
   return sum/arr.length;
}

function mode(numbers) {
    // as result can be bimodal or multi-modal,
    // the returned result is provided as an array
    // mode of [3, 5, 4, 4, 1, 1, 2, 3] = [1, 3, 4]
    var modes = [], count = [], i, number, maxIndex = 0;
 
    for (i = 0; i < numbers.length; i += 1) {
        number = numbers[i];
        count[number] = (count[number] || 0) + 1;
        if (count[number] > maxIndex) {
            maxIndex = count[number];
        }
    }
 
    for (i in count)
       
            if (count[i] === maxIndex) {
                modes.push(Number(i));
       
        }
 
    return modes;
}
function get_max(arr){
    return arr[arr.length-1];
}
function get_min(arr){
    return arr[0];
}
function main()
{
  
  var temp = [20,30,16,25,12,12,12,16,40,42,43];
  temp.push(44);
  temp.push(47);
  var sort_temp = sort(temp);
  for(var i=0;i<sort_temp.length;i++){
      console.log(sort_temp[i]);//sorted temp array
  }
  console.log(get_max(sort_temp));//maximum temprature
  console.log(get_min(sort_temp));//minimmum temprature
  console.log(mean(sort_temp));
  console.log(mode(sort_temp));
  

}
console.log(main());
