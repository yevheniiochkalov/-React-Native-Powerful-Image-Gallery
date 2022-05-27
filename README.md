
# react-native-photo-gallery

This component is a very simple, yet powerfull gallery component including horizontal swiper, photo view, zoom, and pagination.

## Getting started

`$ npm install react-native-photo-gallery --save`

## Usage
```javascript
import Gallery from 'react-native-photo-gallery';

class YourGalleryComponent extends Component {
  render() {
    const data = [
      {
        id: 'first image',
        image: require('./yourImage.jpg'),
        thumb: require('./yourImageThumb.jpg'),
        overlay: <Overlay />
      },
      {
        id: 'Second image',
        image: require('./yourImage2.jpg'),
        thumb: require('./yourImageThumb2.jpg'),
        overlay: <OtherOverlay />
      }
    ];

    return <Gallery data={data} />;
  }
}