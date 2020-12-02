POINT Center(int width,int height) 

{ 

    POINT pt; 

    int screen_width; 

    int screen_height; 

    screen_width = GetSystemMetrics(SM_CXSCREEN); 

    screen_height = GetSystemMetrics(SM_CYSCREEN); 

    pt.x = (screen_width-width)/2; 

    pt.y = (screen_height-height)/2; 

    return pt; 

} 
