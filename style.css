let display = document.getElementById('display');
let currentValue = '';
let currentOperator = '';

function appendToDisplay(value) {
    currentValue += value;
    display.value = currentValue;
}

function clearDisplay() {
    currentValue = '';
    currentOperator = '';
    display.value = '';
}

function calculateResult() {
    try {
        currentValue = eval(currentValue);
        display.value = currentValue;
    } catch (error) {
        display.value = 'Ошибка';
        currentValue = '';
        currentOperator = '';
    }
}
