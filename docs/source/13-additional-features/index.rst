13 Additional features
======================

13-1 Chart reports
------------------

.. image:: ../Images/Screenshot_237.png

.. image:: ../Images/Screenshot_238.png

.. image:: ../Images/Screenshot_239.png

.. image:: ../Images/Screenshot_240.png

.. image:: ../Images/Screenshot_241.png

.. image:: ../Images/Screenshot_242.png

.. image:: ../Images/Screenshot_243.png

.. image:: ../Images/Screenshot_244.png

.. image:: ../Images/Screenshot_245.png

.. image:: ../Images/Screenshot_246.png

.. image:: ../Images/Screenshot_247.png

13-2 JavaScript actions
-----------------------

https://jsonplaceholder.typicode.com/todos

.. image:: ../Images/Screenshot_261.png

.. image:: ../Images/Screenshot_262.png

.. image:: ../Images/Screenshot_263.png

.. image:: ../Images/Screenshot_264.png

.. image:: ../Images/Screenshot_265.png

::

   var _table_ = document.createElement('table'),
     _tr_ = document.createElement('tr'),
     _th_ = document.createElement('th'),
     _td_ = document.createElement('td');

   function buildHtmlTable(arr) {
     var table = _table_.cloneNode(false),
       columns = addAllColumnHeaders(arr, table);
     for (var i = 0, maxi = arr.length; i < maxi; ++i) {
       var tr = _tr_.cloneNode(false);
       for (var j = 0, maxj = columns.length; j < maxj; ++j) {
         var td = _td_.cloneNode(false);
         cellValue = arr[i][columns[j]];
         td.appendChild(document.createTextNode(arr[i][columns[j]] || ''));
         tr.appendChild(td);
       }
       table.appendChild(tr);
     }
     return table;
   }

   function addAllColumnHeaders(arr, table) {
     var columnSet = [],
       tr = _tr_.cloneNode(false);
     for (var i = 0, l = arr.length; i < l; i++) {
       for (var key in arr[i]) {
         if (arr[i].hasOwnProperty(key) && columnSet.indexOf(key) === -1) {
           columnSet.push(key);
           var th = _th_.cloneNode(false);
           th.appendChild(document.createTextNode(key));
           tr.appendChild(th);
         }
       }
     }
     table.appendChild(tr);
     return columnSet;
   }

   var data = JSON.parse(document.querySelector("body").innerText);
   document.querySelector("body").innerHTML=""
   document.body.appendChild(buildHtmlTable(data));

.. image:: ../Images/Screenshot_266.png

.. image:: ../Images/Screenshot_267.png

13-3 CAPTCHA solving service
----------------------------

https://patrickhlauke.github.io/recaptcha/

.. image:: ../Images/Screenshot_248.png

.. image:: ../Images/Screenshot_249.png

.. image:: ../Images/Screenshot_250.png

.. image:: ../Images/Screenshot_251.png

.. image:: ../Images/Screenshot_252.png

.. image:: ../Images/Screenshot_253.png

.. image:: ../Images/Screenshot_254.png

.. image:: ../Images/Screenshot_255.png

.. image:: ../Images/Screenshot_256.png

.. image:: ../Images/Screenshot_257.png

https://2captcha.com/

.. image:: ../Images/Screenshot_258.png

.. image:: ../Images/Screenshot_259.png

.. image:: ../Images/Screenshot_260.png