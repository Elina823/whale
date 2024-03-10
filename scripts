// Add fact button
let getFactButton = document.getElementById('add-fact')
getFactButton.addEventListener('click', function() {
  let facts = document.getElementById('facts')
  let newFact = prompt('Enter a new fact:')
  let createLisItem = document.createElement('li')
  createLisItem.textContent = newFact
  facts.appendChild(createLisItem)
})

// image Slider
let images = ['images/killer whale.webp', 'images/bowhead whale.png', 'images/whale.jpg'] // array
let currentIndex = 0

function changeImage(direction) { // Tool to use to complete a specific task
  if (direction == 'next') {
    currentIndex = (currentIndex + 1) % images.length
  }
  // Make an if-statement that uses 'prev' to go backwards
  if (direction == 'prev') {
    currentIndex = (currentIndex - 1 + images.length) % images.length
  }
  let picture = document.getElementById('picture')
  picture.src = images[currentIndex]
}

// Event listeners for left and right arrows
document.getElementById('left').addEventListener('click', function() {
  changeImage('prev')
})

// Write the right arrow's code
document.getElementById('right').addEventListener('click', function() {
  changeImage('next')
})
