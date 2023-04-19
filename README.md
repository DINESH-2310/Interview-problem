# Interview-problem


const balls = 
  { name: "Baseball",cost:$1},
  { name: "Soccer",cost:$5},,
  { name: "volleyball ball", cost: $6 },
   { name: "football",cost:$9},
  { name: "Basketball",cost:$12},
];
let userAmount= $50;
const purchasedBalls =[];
for (let i = 0; i < balls.length; i++) {
  if (userAmount >= balls[i].price) {
    purchasedBalls.push(balls[i].name);
    userAmount -= balls[i].price;
  }
}
console.log(purchasedBalls)
console.log(userAmount)
