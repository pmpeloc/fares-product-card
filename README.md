# FARES Product Card

Este es un paquete de pruebas de despliegue en NPM

### Pablo Misael Peloc

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'fares-product-card';
```

```
<ProductCard
  product={product}
  // Si comento maxCount evito el bloqueo de incremento
  initialValues={{ count: 4, maxCount: 10 }}>
  {({ reset, increaseBy, count, isMaxCountReached, maxCount }) => (
    <>
      <ProductImage />
      <ProductTitle />
      <ProductButtons />
    </>
  )}
</ProductCard>
```
