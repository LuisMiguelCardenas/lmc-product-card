# lmc-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Luis Miguel Cárdenas

## Ejemplo

```
import { ProductCard,ProductImage,ProductTitle, ProductButtons } from 'lmc-product-card';  
```

```
    <ProductCard
        product={product}
        initialValues={{
          count: 4,
          //maxCount: 15,
        }}
      >
        {({ reset, count, increaseBy, isMaxCountReached, maxCount }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
      </ProductCard>
```