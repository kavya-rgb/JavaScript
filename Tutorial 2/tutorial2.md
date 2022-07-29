# JavaScript Can Change HTML Attributes

    in html:
    ''' 
    <img src="yourlink.png" id="changeMe">
    <button onlick="myFunc()"> </button>
    '''
    in js:
    '''
    myFunc = ()=>{
        document.getElementById('changeMe').src = 'yourextralink.png'
    }
    '''