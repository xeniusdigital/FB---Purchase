# FB---Purchase
FB - Purchase for Shopify Store
#Custom HTML - GTM
<script>
  fbq('track', 'Purchase', {
    value: {{DLV - Revenue}},
    currency: 'GBP',
    content_ids: '{{DLV - Transaction ID}}',
    content_type: 'product',
    contents: [
        {
            id: '{{JS - Purchase - ID}}',
            quantity: {{JS - Purchase - Quantity}},
            item_price: {{DLV - Product Page - Price}},
            content_name: '{{JS - Purchase - Name}}'
        }
    ],
  });
</script>
