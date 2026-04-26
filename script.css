const message = `Semoga hari harimu selalu dipenuhi kebaikan dan keindahan,
semoga semesta berpihak padamu, dan setiap langkahmu dimudahkan menuju masa depan yang cerah.

Teruslah berkembang, terus melangkah, dan temukan kebahagiaanmu.

from leota Pramudya`;

function showLetter() {
  document.getElementById("introText").style.opacity = 0;
  document.querySelector(".btn").style.display = "none";

  setTimeout(() => {
    const letterBox = document.getElementById("letterBox");
    const typedText = document.getElementById("typedText");
    letterBox.style.display = "block";
    let i = 0;

    function typeWriter() {
      if (i < message.length) {
        typedText.innerHTML += message.charAt(i);
        i++;
        setTimeout(typeWriter, 30);
      }
    }

    typeWriter();
  }, 600);
}
