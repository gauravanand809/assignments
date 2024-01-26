let count = 0;

// Function to update and display the counter
function updateCounter() {
  console.log("Counter:", count);
  count++;

  // Uncomment the following line if you want the counter to stop after a certain number of iterations (e.g., 10 iterations)
  // if (count === 10) clearInterval(counterInterval);
}

// Use a for loop to simulate the counter
for (let i = 0; i < 10; i++) {
  setTimeout(updateCounter, i * 1000);
}
