# Q:
    var val = 'smtg';
    console.log('Value is ' + (val === 'smtg') ? 'Something' : 'Nothing');
# A:
    'Somethind'
# P:
    + 优先级高于 ?
    => 'Value is true' ? 'Somthing' : 'Nonthing'