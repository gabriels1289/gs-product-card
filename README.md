# GS-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Gabriel Schvert

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'gs-product-card;
```

```
<ProductCard
  key={ product.id }
  product={ product }
  initialValues={{
    count: 4,
    // maxCount: 10
  }}
>
  {
    ({ reset, increaseBy, count, maxCount, isMaxCountReached }) => (
      <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />
      </>
    )
  }
</ProductCard>
```