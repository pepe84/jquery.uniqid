jquery.uniqid
=============

jQuery plugin to generate a random unique id

Examples:

    $('h1').uniqid();               // Set alphanumeric id (if id not exists)
    $('h1').uniqid(true);           // Set v4 UUID (if id not exists)
    $('h1'),uniqid(false, true);    // Set alphanumeric id (replacing current id)

