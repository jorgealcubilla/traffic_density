# traffic_density
Website getting image from traffic camera and returning traffic density

Link to this website: https://jorgealcubilla.github.io/traffic_density/

$.ajax({
        async:false,
        url: 'C:/Users/JORGE/Desktop/TFM_final/TRANCOS/web_data/density.txt',
        dataType: 'text',
        success: function(data) 
        {
        $('element').append(data);
            }
        });
