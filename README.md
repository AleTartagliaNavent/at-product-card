#-AT-Product-card

Este es un paquete de pruebas de despliegue en NPM

### Ale Tartaglia

## Ejemplo

```
import {
ProductCard,
ProductImage,
ProductTitle,
ProductButtons
} from 'at-product-card'
```

```
<ProductCard
        
        product={product}
        initialValues={{
          count: 4,
          maxCount: 10,
        }}
      >
        {({
          count,
          isMaxCountReached,
          maxCount,
          increaseBy,
          reset,
        }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />

          </>
        )}
      </ProductCard>
```