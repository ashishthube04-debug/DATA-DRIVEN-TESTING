# DATA-DRIVEN-TESTING

COMPANY NAME : CODTECH IT SOLUTION 

NAME : ASHISH EKNATH THUBE 

INTERN ID : CTIS2824

DOMAIN : DATA-DRIVEN-TESTING  

DURATION : 1 MONTH 

MENTOR : NEELA SANTOSH

DISCRIPTION OF TASK HOW YOU PERFORMED AND WHAT YOU HAVE DONE AND PASTE CODES OF OUTPUT

OUTPUT...

pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});

pm.test("Response time is less than 1000ms", function () {
    pm.expect(pm.response.responseTime).to.be.below(1000);
});

pm.test("Response is an array", function () {
    pm.expect(pm.response.json()).to.be.an('array');
});
