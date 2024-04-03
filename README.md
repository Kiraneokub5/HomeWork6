
// Почніть з отримання власної версії коду.

// Почніть із заповнення коду функції upDate.
function upDate(previewPic){
    // Отримайте alt та src зображення, над яким навели курсор.
    var altText = previewPic.alt;
    var imageUrl = previewPic.src;

    // Оновіть текст та фонове зображення відповідно до вибраного зображення.
    document.getElementById('image').style.backgroundImage = "url('" + imageUrl + "')";
    document.getElementById('imageText').innerHTML = altText;
}

// Допишіть код функції скасування.
function unDo(){
    // Скасуйте зміни та поверніть початкові значення.
    document.getElementById('image').style.backgroundImage = "url('')";
    document.getElementById('imageText').innerHTML = "Наведіть курсор на зображення нижче, щоб відобразити його тут";
}
