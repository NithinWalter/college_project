// JavaScript code for website

// Search form functionality
const searchIcon = document.getElementById('search-icon');
const searchForm = document.getElementById('search-form');
const searchBox = document.getElementById('search-box');
const closeSearch = document.getElementById('close');

searchIcon.addEventListener('click', () => {
    searchForm.style.display = 'block';
    searchBox.focus();
});

closeSearch.addEventListener('click', () => {
    searchForm.style.display = 'none';
    searchBox.value = '';
});

// Random Artwork feature
const randomArtworkButton = document.getElementById('random-artwork-button');
const artworkImages = document.querySelectorAll('.artwork-image');
const artworkDescriptions = document.querySelectorAll('.artwork-description');

randomArtworkButton.addEventListener('click', () => {
    // Hide all artwork descriptions
    artworkDescriptions.forEach(description => {
        description.style.display = 'none';
    });

    // Generate a random index to display a random artwork
    const randomIndex = Math.floor(Math.random() * artworkImages.length);

    // Show the randomly selected artwork and its description
    artworkImages[randomIndex].style.display = 'block';
    artworkDescriptions[randomIndex].style.display = 'block';
});

