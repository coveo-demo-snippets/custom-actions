# custom-actions

The newResultDisplayed event can be invoked in two ways:

a.

    function handleNewResultDisplayed(e, args) {

new div = 
}

   Coveo.$$(document.getElementById('search')).on(Coveo.ResultListEvents.newResultDisplayed, handleNewResultDisplayed);
 

b.

OR like this:

$('.CoveoSearchInterface').on('newResultDisplayed', function (e, args) {



    });
