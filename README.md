# Modaldialog.js
IE Modaldialog now can work on modern browsers with the same behavior as IE9
```
async function popup(url){ // modal.html for example 
await window.showModalDialog(url,500,400,args);
}

// modal.html

function onSubmit(){
// thats how to close the modal dialog box.
window.ClosePopup();
}
```
