# traffic_density
Website getting image from traffic camera and returning traffic density

Link to this website: https://jorgealcubilla.github.io/traffic_density/

$.ajax({
        async:false,
        url: '/web_data/density.txt',
        dataType: 'text',
        success: function(data) 
        {
        $('element').append(data);
            }
        });

<img src="web_data/img.jpg" alt="traffic_cam">
