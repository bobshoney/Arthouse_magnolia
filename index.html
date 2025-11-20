import React, { useState } from 'react';
import { ShoppingCart, X, Plus, Minus } from 'lucide-react';

const ArtGallery = () => {
  const [cart, setCart] = useState([]);
  const [showCart, setShowCart] = useState(false);
  const [selectedArt, setSelectedArt] = useState(null);

  const artworks = [
    {
      id: 1,
      title: "Sunset Dreams",
      artist: "Elena Rodriguez",
      price: 1200,
      medium: "Oil on Canvas",
      size: "24\" x 36\"",
      image: "https://images.unsplash.com/photo-1541961017774-22349e4a1262?w=800&q=80",
      description: "A vibrant exploration of color and light capturing the essence of twilight."
    },
    {
      id: 2,
      title: "Urban Pulse",
      artist: "Elena Rodriguez",
      price: 950,
      medium: "Acrylic on Canvas",
      size: "20\" x 30\"",
      image: "https://images.unsplash.com/photo-1547826039-bfc35e0f1ea8?w=800&q=80",
      description: "Dynamic cityscape reflecting the energy of metropolitan life."
    },
    {
      id: 3,
      title: "Ethereal Waters",
      artist: "Elena Rodriguez",
      price: 1500,
      medium: "Oil on Canvas",
      size: "30\" x 40\"",
      image: "https://images.unsplash.com/photo-1579783902614-a3fb3927b6a5?w=800&q=80",
      description: "A serene meditation on the fluidity and power of water."
    },
    {
      id: 4,
      title: "Golden Hour",
      artist: "Elena Rodriguez",
      price: 850,
      medium: "Watercolor",
      size: "18\" x 24\"",
      image: "https://images.unsplash.com/photo-1578301978693-85fa9c0320b9?w=800&q=80",
      description: "Delicate brushwork capturing the magic of late afternoon light."
    },
    {
      id: 5,
      title: "Abstract Harmony",
      artist: "Elena Rodriguez",
      price: 1100,
      medium: "Mixed Media",
      size: "24\" x 24\"",
      image: "https://images.unsplash.com/photo-1549887534-1541e9326642?w=800&q=80",
      description: "Bold geometric forms dancing in perfect compositional balance."
    },
    {
      id: 6,
      title: "Mountain Majesty",
      artist: "Elena Rodriguez",
      price: 1800,
      medium: "Oil on Canvas",
      size: "36\" x 48\"",
      image: "https://images.unsplash.com/photo-1547234935-80c7145ec969?w=800&q=80",
      description: "Majestic peaks rendered with dramatic light and atmospheric depth."
    }
  ];

  const addToCart = (artwork) => {
    const existing = cart.find(item => item.id === artwork.id);
    if (existing) {
      setCart(cart.map(item => 
        item.id === artwork.id 
          ? {...item, quantity: item.quantity + 1}
          : item
      ));
    } else {
      setCart([...cart, {...artwork, quantity: 1}]);
    }
  };

  const updateQuantity = (id, delta) => {
    setCart(cart.map(item => {
      if (item.id === id) {
        const newQty = item.quantity + delta;
        return newQty > 0 ? {...item, quantity: newQty} : item;
      }
      return item;
    }).filter(item => item.quantity > 0));
  };

  const removeFromCart = (id) => {
    setCart(cart.filter(item => item.id !== id));
  };

  const cartTotal = cart.reduce((sum, item) => sum + (item.price * item.quantity), 0);
  const cartCount = cart.reduce((sum, item) => sum + item.quantity, 0);

  return (
    <div className="min-h-screen bg-gradient-to-br from-slate-50 to-slate-100">
      {/* Header */}
      <header className="bg-white shadow-md sticky top-0 z-40">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-6">
          <div className="flex justify-between items-center">
            <div>
              <h1 className="text-3xl font-bold text-gray-900">Elena Rodriguez</h1>
              <p className="text-gray-600 mt-1">Contemporary Artist</p>
            </div>
            <button
              onClick={() => setShowCart(!showCart)}
              className="relative bg-slate-900 text-white px-6 py-3 rounded-lg hover:bg-slate-800 transition-colors flex items-center gap-2"
            >
              <ShoppingCart size={20} />
              <span>Cart</span>
              {cartCount > 0 && (
                <span className="absolute -top-2 -right-2 bg-red-500 text-white rounded-full w-6 h-6 flex items-center justify-center text-sm font-bold">
                  {cartCount}
                </span>
              )}
            </button>
          </div>
        </div>
      </header>

      {/* Main Content */}
      <main className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <div className="mb-12 text-center">
          <p className="text-lg text-gray-700 max-w-3xl mx-auto">
            Explore a curated collection of original paintings and mixed media works. 
            Each piece is an authentic original, signed by the artist.
          </p>
        </div>

        {/* Art Grid */}
        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          {artworks.map(art => (
            <div 
              key={art.id}
              className="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-2xl transition-shadow cursor-pointer"
              onClick={() => setSelectedArt(art)}
            >
              <div className="aspect-square overflow-hidden bg-gray-100">
                <img 
                  src={art.image} 
                  alt={art.title}
                  className="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
                />
              </div>
              <div className="p-6">
                <h3 className="text-xl font-bold text-gray-900 mb-2">{art.title}</h3>
                <p className="text-gray-600 text-sm mb-3">{art.medium} • {art.size}</p>
                <div className="flex justify-between items-center">
                  <span className="text-2xl font-bold text-slate-900">${art.price.toLocaleString()}</span>
                  <button
                    onClick={(e) => {
                      e.stopPropagation();
                      addToCart(art);
                    }}
                    className="bg-slate-900 text-white px-4 py-2 rounded-lg hover:bg-slate-800 transition-colors"
                  >
                    Add to Cart
                  </button>
                </div>
              </div>
            </div>
          ))}
        </div>
      </main>

      {/* Shopping Cart Sidebar */}
      {showCart && (
        <div className="fixed inset-0 z-50 overflow-hidden">
          <div className="absolute inset-0 bg-black bg-opacity-50" onClick={() => setShowCart(false)} />
          <div className="absolute right-0 top-0 bottom-0 w-full max-w-md bg-white shadow-2xl flex flex-col">
            <div className="p-6 border-b flex justify-between items-center">
              <h2 className="text-2xl font-bold">Shopping Cart</h2>
              <button onClick={() => setShowCart(false)} className="text-gray-500 hover:text-gray-700">
                <X size={24} />
              </button>
            </div>
            
            <div className="flex-1 overflow-y-auto p-6">
              {cart.length === 0 ? (
                <p className="text-gray-500 text-center mt-8">Your cart is empty</p>
              ) : (
                <div className="space-y-4">
                  {cart.map(item => (
                    <div key={item.id} className="flex gap-4 bg-gray-50 p-4 rounded-lg">
                      <img src={item.image} alt={item.title} className="w-20 h-20 object-cover rounded" />
                      <div className="flex-1">
                        <h3 className="font-semibold text-gray-900">{item.title}</h3>
                        <p className="text-sm text-gray-600">${item.price.toLocaleString()}</p>
                        <div className="flex items-center gap-3 mt-2">
                          <button
                            onClick={() => updateQuantity(item.id, -1)}
                            className="w-7 h-7 flex items-center justify-center bg-gray-200 rounded hover:bg-gray-300"
                          >
                            <Minus size={14} />
                          </button>
                          <span className="font-semibold">{item.quantity}</span>
                          <button
                            onClick={() => updateQuantity(item.id, 1)}
                            className="w-7 h-7 flex items-center justify-center bg-gray-200 rounded hover:bg-gray-300"
                          >
                            <Plus size={14} />
                          </button>
                          <button
                            onClick={() => removeFromCart(item.id)}
                            className="ml-auto text-red-500 hover:text-red-700 text-sm"
                          >
                            Remove
                          </button>
                        </div>
                      </div>
                    </div>
                  ))}
                </div>
              )}
            </div>

            {cart.length > 0 && (
              <div className="border-t p-6 bg-gray-50">
                <div className="flex justify-between items-center mb-4">
                  <span className="text-lg font-semibold">Total:</span>
                  <span className="text-2xl font-bold">${cartTotal.toLocaleString()}</span>
                </div>
                <button className="w-full bg-slate-900 text-white py-4 rounded-lg hover:bg-slate-800 transition-colors font-semibold">
                  Proceed to Checkout
                </button>
              </div>
            )}
          </div>
        </div>
      )}

      {/* Artwork Detail Modal */}
      {selectedArt && (
        <div className="fixed inset-0 z-50 overflow-y-auto bg-black bg-opacity-75 flex items-center justify-center p-4">
          <div className="bg-white rounded-xl max-w-4xl w-full max-h-[90vh] overflow-y-auto">
            <div className="sticky top-0 bg-white border-b p-4 flex justify-between items-center">
              <h2 className="text-2xl font-bold">{selectedArt.title}</h2>
              <button onClick={() => setSelectedArt(null)} className="text-gray-500 hover:text-gray-700">
                <X size={24} />
              </button>
            </div>
            <div className="p-6">
              <div className="grid md:grid-cols-2 gap-8">
                <div>
                  <img 
                    src={selectedArt.image} 
                    alt={selectedArt.title}
                    className="w-full rounded-lg shadow-lg"
                  />
                </div>
                <div>
                  <p className="text-gray-700 mb-4">{selectedArt.description}</p>
                  <div className="space-y-3 mb-6">
                    <div className="flex justify-between border-b pb-2">
                      <span className="font-semibold">Artist:</span>
                      <span>{selectedArt.artist}</span>
                    </div>
                    <div className="flex justify-between border-b pb-2">
                      <span className="font-semibold">Medium:</span>
                      <span>{selectedArt.medium}</span>
                    </div>
                    <div className="flex justify-between border-b pb-2">
                      <span className="font-semibold">Size:</span>
                      <span>{selectedArt.size}</span>
                    </div>
                    <div className="flex justify-between border-b pb-2">
                      <span className="font-semibold">Price:</span>
                      <span className="text-2xl font-bold">${selectedArt.price.toLocaleString()}</span>
                    </div>
                  </div>
                  <button
                    onClick={() => {
                      addToCart(selectedArt);
                      setSelectedArt(null);
                      setShowCart(true);
                    }}
                    className="w-full bg-slate-900 text-white py-4 rounded-lg hover:bg-slate-800 transition-colors font-semibold"
                  >
                    Add to Cart
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      )}
    </div>
  );
};

export default ArtGallery;
