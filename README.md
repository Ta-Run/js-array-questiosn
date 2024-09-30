# js-array-questiosn
Find Highest and lowest and second Highest and second lowest Value from array
const arr = [6,2,3,5,7,8,4]
let swapValue = 0
for(let i=0;i<arr.length;i++){
    for(let j=i+1;j<arr.length;j++){
      if( arr[i] > arr[j]){
        // swapValue = arr[j]
        // arr[j]=arr[i]
        // arr[i] = swapValue
        
        [arr[i], arr[j]] = [arr[j] , arr[i]] 
        
      }
    }
}
//second highest number from arrry
console.log(arr[arr.length-2])
//first highest value from array
console.log(arr[arr.length-1])
//lowest value of array
console.log(arr[0])
//second lowest value of array 
console.log(arr[1])

