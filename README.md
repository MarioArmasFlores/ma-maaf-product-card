# maaf-product-card

Este es un paquete de pruebas de despliegue en NPM 

### Mario Armas

## Ejemplo

```
import {
  ProductCard,
  ProductImage,
  ProductTitle,
  ProductButtons,
} from 'maaf-product-card'
```

```
<ProductCard
        product={product}
        initialValues={{
          count: 4,
          // maxCount: 10,
        }}
      >
        {({ reset, count, increaseBy, isMaxCountReached }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductsButtons />
          </>
        )}
      </ProductCard>

```
