# smthng
Something Important

"use strict";

let shopCustomers = [
    {name: 'Martin', balance: 120, age: 21, alcoholName: 'martini', alcoholCount: 2},
    {name: 'Jack', balance: 200, age: 25, alcoholName: 'jack_Daniels', alcoholCount: 3},
    {name: 'Jim', balance: 180, age: 35, alcoholName: 'jim_Beam', alcoholCount: 2},
    {name: 'James', balance: 210, age: 31, alcoholName: 'jameson', alcoholCount: 2},
    {name: 'John', balance: 250, age: 29, alcoholName: 'johnnie_Walker', alcoholCount: 3},
    {name: 'Glen', balance: 215, age: 26, alcoholName: 'glenfiddich', alcoholCount: 3},
    {name: 'Ralph', balance: 260, age: 27, alcoholName: 'laphroaig', alcoholCount: 1},
    {name: 'Louis', balance: 350, age: 25, alcoholName: 'beringer', alcoholCount: 4},
    {name: 'Karl', balance: 370, age: 23, alcoholName: 'fetzer', alcoholCount: 4},
    {name: 'Bernard', balance: 123, age: 21, alcoholName: 'eagle_Creek', alcoholCount: 2},
];

let priceForOneItem = {
    martini: 12.3,
    jack_Daniels: 20.2,
    jim_Beam: 20.1,
    jameson: 19.8,
    johnnie_Walker: 20.4,
    glenfiddich: 22.4,
    laphroaig: 25.6,
    beringer: 25.2,
    fetzer: 29.1,
    eagle_Creek: 21.2,
};

function getArrOfParams (arr, paramName) {     // Функция getArrOfParams вкючает массив arr и переменную paramName: 
    return arr.map(arrItem => {                // возвращает arrItem, который пробегается  через .map и берет paramName, который тоже возвращаем.
       return arrItem[paramName];
    });
}

function init (customers) {
    customers.forEach(function (customerAge) {
        return 
    });


    function functionName (customer) {

        getPriceFunctionName();
    };

    function getPriceFunctionName(param) {

    };
}

init(shopCustomers);


function init (customers) {
    customers.forEach (function (customerName) {
        console.log(customerName)
    });
    
    function customerName (customer) {
        getPriceFunctionName(priceForOneItem);
    }
    
    function getPriceFunctionName(param) {
        
    }
}
    
init(shopCustomers);
