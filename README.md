function revealAnswer(answer) {
    document.getElementById('response').style.display = 'block';
    if (answer === 'Yes') {
        document.getElementById('response').innerText = 'Yay! Let go to the movie this sunday And hug u:33.';
    } else {
        document.getElementById('response').innerText = 'No worries, maybe we can doodle another time.';
    }
}
