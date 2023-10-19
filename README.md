#am-Product-Card

Este es un paquete de pruebas e despliegue en NPM

### Anibal Mancilla 

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'am-product-card';
```

```
<ProductCard product = { product }
  initialValues = {{
    count: 4,
    maxCount: 10
  }}>
    {
      ( { reset, count, increaseBy, isMaxCountReached} ) => (
        <>
          <ProductImage />
          <ProductTitle />
          <ProductButtons />
        </>
      )
    }
</ProductCard>
```