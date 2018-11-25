function clickBySelector(selectorVal) {
	let elementBySelector = document.querySelector(selectorVal);
	elementBySelector.click();
}

function clickByXpath(selectorVal) {
  	let elementByXpath = document.evaluate(selectorVal, document, null, XPathResult.FIRST_ORDERED_NODE_TYPE, null).singleNodeValue;
  	elementByXpath.click();
}

/*clickByXpath("//button[contains(text(), 'Lanjut')]");*/
/*clickBySelector("#checkout-payment_method-type-Transfer");*/
/*clickByXpath("//li[contains(text(), 'Bank BCA')]");*/
/*clickByXpath("//button[contains(text(), 'Bayar Sekarang')]");*/

setTimeout(function () {
	clickByXpath("//button[contains(text(), 'Lanjut')]");
    setTimeout(function () {
    	clickBySelector("#checkout-payment_method-type-Transfer");
	    setTimeout(function () {
	    	clickByXpath("//li[contains(text(), 'Bank BCA')]");
		    setTimeout(function () {
		    	clickByXpath("//button[contains(text(), 'Bayar Sekarang')]");
			}, 3000);	
		}, 3000);
	}, 3000);
}, 3000);

/* rubah saja string didalam ini maka bot akan menginject pada halaman */
