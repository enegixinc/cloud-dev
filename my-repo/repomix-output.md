This file is a merged representation of a subset of the codebase, containing files not matching ignore patterns, combined into a single document by Repomix.
The content has been processed where comments have been removed, empty lines have been removed, line numbers have been added, content has been compressed (code blocks are separated by ⋮---- delimiter).

# File Summary

## Purpose
This file contains a packed representation of a subset of the repository's contents that is considered the most important context.
It is designed to be easily consumable by AI systems for analysis, code review,
or other automated processes.

## File Format
The content is organized as follows:
1. This summary section
2. Repository information
3. Directory structure
4. Repository files (if enabled)
5. Multiple file entries, each consisting of:
  a. A header with the file path (## File: path/to/file)
  b. The full contents of the file in a code block

## Usage Guidelines
- This file should be treated as read-only. Any changes should be made to the
  original repository files, not this packed version.
- When processing this file, use the file path to distinguish
  between different files in the repository.
- Be aware that this file may contain sensitive information. Handle it with
  the same level of security as you would the original repository.

## Notes
- Some files may have been excluded based on .gitignore rules and Repomix's configuration
- Binary files are not included in this packed representation. Please refer to the Repository Structure section for a complete list of file paths, including binary files
- Files matching these patterns are excluded: node_modules, src/assets, src/locales, src/styles
- Files matching patterns in .gitignore are excluded
- Files matching default ignore patterns are excluded
- Code comments have been removed from supported file types
- Empty lines have been removed from all files
- Line numbers have been added to the beginning of each line
- Content has been compressed - code blocks are separated by ⋮---- delimiter
- Files are sorted by Git change count (files with more changes are at the bottom)

# Directory Structure
```
public/
  .htaccess
  logo.svg
  manifest.example.json
  multi-tab-worker.js
src/
  components/
    aside/
      panelTitle.vue
    bottomSheets/
      logoutSheet.vue
    customs/
      customBtn.vue
      customCard.vue
      customReceipt.vue
      emptyScreen.vue
      kpiCard.vue
      sectionTitle.vue
    dialogs/
      cart/
        cart-suspend-dialog.vue
      base-dialog.vue
      declined-order-dialog.vue
      dialog-manager.vue
      events.ts
      product-name.vue
      vcs-dialog.vue
    mainScreen/
      header-section/
        headerSection.vue
        search-product.vue
      bottom-cards.vue
      categoriesCarousel.vue
    workers/
      clock/
        clock.vue
        timeWorker.ts
    appliedCoupons.vue
    appLogo.vue
    calculator.vue
    cartPreview.vue
    cartProductCard.vue
    changeLangDemo.vue
    couponItem.vue
    dataPlaceholder.vue
    downloadTrolly.vue
    feedbackSlider.vue
    iconData.vue
    loyaltyMembership.vue
    newCoupon.vue
    orderSummary.vue
    productCardWithoutPic.vue
    quickActions.vue
    quickProductsAdd.vue
    redeemSlider.vue
    simpleKeyboard.vue
    split-payments.vue
    StatusIndicator.vue
    transaction-subbmiting.vue
    trolleyCoupon.vue
    updateApp.vue
  composables/
    cookies.js
    prefetchMedia.ts
  features/
    app-mode/
      backend-status-indicator.vue
      backend-status-topic.ts
      check.ts
    items/
      check.ts
      store.ts
    multi-tab/
      multi-tab-broadcast.ts
      multi-tab.vue
    payment-methods/
      check.ts
    printing/
      order/
        cash-section.vue
        cashier-section.vue
        declined-receipt.vue
        knet-section.vue
        order-receipt.vue
        refund-receipt.vue
        shared-section.vue
      receipts/
        decline-receipt.vue
        reconciliation-receipt.vue
        refund-receipt.vue
        sale-receipt.vue
      base-receipt.vue
      events.ts
      helpers.ts
      printing-feature.ts
      state.ts
      types.ts
    reinstall/
      reinstall-auth-dialog.vue
      reinstall-process-dialog.vue
      use-reinstall.ts
    sync-check/
      state.ts
      sync-check-dialog.vue
      use-health-check.ts
    tests/
      posthog.spec.ts
    usecases/
      employee/
        events.ts
      payments/
        knet/
          automatic/
            knet-connection-indicator.vue
      scanner/
        events.ts
    users/
      check.ts
    void-reasons/
      cart-void-dialog.vue
      check.ts
      store.ts
    after-auth-employee-features.ts
    openCashDrawer.ts
    openreplay.ts
    posthog.ts
    pre-auth-features.ts
    session-trackers.ts
  layouts/
    clientView.vue
    employeeView.vue
    emptyView.vue
  modules/
    advertisement/
      banner-carousel.vue
      video-screen.vue
    auth/
      events.ts
      index.ts
      store.ts
      types.ts
    loyalty/
      assets/
        compare-arrows.vue
        crown.svg
        loyality-card-01.svg
      components/
        cashier-view/
          client-phone-input.vue
          loyalty-card.vue
          loyalty-header.vue
          loyalty-membership.vue
          loyalty-summary.vue
          redeem-slider.vue
        client-view/
          client-loyalty-card.vue
          client-membership.vue
          client-unAuth-loyalty-card.vue
      store/
        loyalty-store.ts
      tests/
        loyalty-store.spec.ts
    payments/
      assets/
        credit.svg
        deliveroo.svg
        knet-icon.svg
        pay-cash.svg
        talabat.svg
      checkout-button.vue
      payments-store.ts
    quick-list/
      health-check.ts
      store.ts
    settings/
      health-check.ts
      store.ts
      version-update-dialog.vue
      version-update.ts
  pages/
    cartPage.vue
    clientHomePage.vue
    loginPage.vue
    notFound.vue
    refundPage.vue
    sessionPage.vue
    stashedCart.vue
    testPage.vue
    transactionPage.vue
  plugins/
    shared/
      index.ts
      utils.ts
      vanilla.ts
    axios.js
    i18n.js
    index.js
    pinia.ts
    vuetify.js
  router/
    index.js
  services/
    api.ts
    auth.ts
    navigator.ts
  store/
    coupons/
      index.ts
      state.ts
    customer/
      actions.ts
      state.ts
      types.ts
    transaction/
      actions.ts
      index.ts
      state.ts
      types.ts
    app-machine.ts
    bottom-cards.ts
    clientScreen.ts
    global.ts
    stashed-transactions.ts
    uiUpdate.ts
  utils/
    debouncer.ts
    extractMediaUrls.ts
    path.ts
    runAfterStoreHydrated.ts
    sync.ts
    utils.spec.ts
    utils.ts
  views/
    actionPanels/
      cart/
        checkoutView.vue
        couponsView.vue
        mainCartPanel.vue
      refundPanel.vue
      stashedCartsPanel.vue
      transactionsPanel.vue
    actionPanel.vue
    cartProducts.vue
    clientActionPanel.vue
    sideNav.vue
  App.vue
  env.ts
  main.js
  main.spec.ts
  shims-vue.d.ts
.env.example
.eslintrc.json
Dockerfile
index.html
project.json
tsconfig.app.json
tsconfig.json
tsconfig.spec.json
vite.config.ts
```

# Files

## File: public/.htaccess
```
<IfModule mod_rewrite.c>
    <IfModule mod_negotiation.c>
        Options -MultiViews -Indexes
    </IfModule>

    RewriteEngine On

    # Handle Authorization Header
    RewriteCond %{HTTP:Authorization} .
    RewriteRule .* - [E=HTTP_AUTHORIZATION:%{HTTP:Authorization}]

    # Redirect Trailing Slashes If Not A Folder...
    RewriteCond %{REQUEST_FILENAME} !-d
    RewriteCond %{REQUEST_URI} (.+)/$
    RewriteRule ^ %1 [L,R=301]

    # Send Requests To Front Controller...
    RewriteCond %{REQUEST_FILENAME} !-d
    RewriteCond %{REQUEST_FILENAME} !-f
    RewriteRule ^ index.html [L]
</IfModule>

# Force latest sw.js to be fetched every time
<FilesMatch "sw.js">
    Header set Cache-Control "no-store, no-cache, must-revalidate, proxy-revalidate"
    Header set X-Debug-Cache-Control "Applied on Server"
</FilesMatch>
```

## File: public/logo.svg
```
<svg xmlns="http://www.w3.org/2000/svg" width="1" height="1" viewBox="-1 -3 38 38">
    <g id="logo" transform="translate(22054.189 5267.175)">
        <path id="Path_172751" d="M148.65,399.871a2.523,2.523,0,1,0-2.523,2.523,2.523,2.523,0,0,0,2.523-2.523" transform="translate(-22173.852 -5637.197)" fill="#ed7d00"/>
        <path id="Path_172752" d="M96,399.871a2.523,2.523,0,1,0,2.523-2.523A2.523,2.523,0,0,0,96,399.871" transform="translate(-22138.576 -5637.197)" fill="#f58220"/>
        <path id="Path_172753" d="M52.1,294.809l5.467,2.264,2.54,19.289a1.835,1.835,0,0,0,1.819,1.6h19.72a1.56,1.56,0,0,0,0-3.12H63.579l-.411-3.12h18.3a1.56,1.56,0,0,0,1.441-.963L87.278,300.2a1.56,1.56,0,0,0-1.441-2.157H61.369l-.248-1.887A1.836,1.836,0,0,0,60,294.7l-6.646-2.753a1.6,1.6,0,0,0-2.079.775,1.56,1.56,0,0,0,.825,2.082m27.435,6.358h3.67L80.131,308.6H76.46Zm-7.341,0h3.67L72.79,308.6H69.12Zm-3.67,0L65.45,308.6H62.758l-.979-7.432Z" transform="translate(-22105.33 -5559)" fill="#f58220"/>
    </g>
</svg>
```

## File: public/manifest.example.json
```json
{
  "name": "Trolley POS",
  "icons": [
    {
      "src": "logo.svg",
      "sizes": "any"
    }
  ],
  "display": "standalone",
  "start_url": "https://pos-dev.trolley.systems/cart"
}
```

## File: public/multi-tab-worker.js
```javascript
ports.push(port);
console.log('originalPort', originalPort);
⋮----
port.postMessage('original-tab');
⋮----
port.postMessage('already-open');
originalPort.postMessage('focus-original');
⋮----
port.onclose = () => {
ports = ports.filter((p) => p !== port);
```

## File: src/components/aside/panelTitle.vue
```vue
<script setup lang="ts">
import { computed, defineComponent, defineProps } from 'vue';
import AppLogo from '../appLogo.vue';
import { globalStore } from '../../store/global';
import { useI18n } from 'vue-i18n';
import { dialogTopic } from '../dialogs/events';
import { useSettings } from '../../modules/settings/store';
const { t } = useI18n();
defineComponent({
  components: {
    AppLogo,
  },
});
const props = defineProps({
  title: {
    type: String,
    default: 'actions_panel',
  },
  icon: String,
});
const localizedTitle = computed(() =>
  globalStore.tab ? t(globalStore.tab) : t(props.title),
);
</script>
<template>
  <div class="d-flex justify-space-between align-center panel-title pb-1">
    <p id="branch-title">
      {{ useSettings()?.settings?.warehouse }}
    </p>
    <button
      @click="dialogTopic.publish('SHOW_VCS_DIALOG', {})"
      class="btn-logo"
    >
      <AppLogo />
    </button>
  </div>
</template>
⋮----
{{ useSettings()?.settings?.warehouse }}
⋮----
<style scoped>
#branch-title {
  font-size: 14px;
}
.btn-logo {
  width: 100px;
  height: 100%;
}
</style>
```

## File: src/components/bottomSheets/logoutSheet.vue
```vue
<script lang="ts" setup>
import { logout } from '../../services/auth';
import { reactive, ref, watch } from 'vue';
import { publish, subscribe } from '@enegix/events';
import { AUTH_EVENTS } from '../../modules/auth/events';
import { PRINT_RECONCILIATION_RECEIPT } from '../../features/printing/events';
import { auth } from '../../modules/auth';
import { validateNumberInput } from '../../../../../libs/utils/src/lib/validators';
const sheet = ref(false);
const loading = ref(false);
const step = ref(1);
const formData = reactive<{
  cash_out: number | null;
  end_knet: number | null;
  type: number;
}>({
  cash_out: null,
  end_knet: null,
  type: 0,
});
function next(sessionType: number) {
  formData.type = sessionType;
  step.value = 2;
}
function confirm() {
  loading.value = true;
  publish(PRINT_RECONCILIATION_RECEIPT);
  logout(formData.cash_out, formData.end_knet, formData.type).then(() => {
    loading.value = false;
  });
}
function cancel() {
  step.value = 1;
  formData.cash_out = null;
  formData.end_knet = null;
  formData.type = 0;
  sheet.value = !sheet.value;
}
const isConfirmDisabled = ref(false);
watch(
  formData,
  ({ cash_out, end_knet }) => {
    const isValid =
      validateNumberInput(cash_out) && validateNumberInput(end_knet);
    isConfirmDisabled.value = !isValid;
    if (isValid) {
      auth().state.cash_out.value = cash_out;
      auth().state.knet_out.value = end_knet;
    }
  },
  {
    immediate: true,
  },
);
subscribe(AUTH_EVENTS.END_SHIFT, () => {
  sheet.value = !sheet.value;
});
</script>
<template>
  <v-bottom-sheet v-model="sheet">
    <v-card class="rounded-t-xl py-5">
      <v-form @submit.prevent="confirm">
        <div v-if="step === 1">
          <v-card-title class="text-center text-capitalize mb-4">
            End of Day Session?
            <p class="text-body-2 text-grey">
              Select "End Of Day" if you want to close out the day
            </p>
          </v-card-title>
          <v-card-actions class="d-flex justify-center">
            <v-btn
              variant="outlined"
              color="primary"
              size="x-large"
              class="text-uppercase"
              width="300"
              type="button"
              @click="next(0)"
            >
              End of Shift
            </v-btn>
            <v-btn
              :loading="loading"
              variant="outlined"
              color="primary"
              size="x-large"
              class="text-uppercase"
              width="300"
              type="button"
              @click="next(3)"
            >
              End of Day
            </v-btn>
          </v-card-actions>
        </div>
        <div v-if="step === 2">
          <v-card-title class="text-center text-capitalize mb-4">
            Confirm your cash out & knet end balance to proceed
            <p class="text-body-2 text-grey">
              This will close your current session and cancel any active cart
            </p>
          </v-card-title>
          <v-card-text>
            <v-row align="center" justify="center">
              <v-col cols="4">
                <v-text-field
                  variant="outlined"
                  v-model="formData.cash_out"
                  :rules="[validateNumberInput]"
                  label="Cash Out"
                  type="number"
                  prepend-inner-icon="mdi mdi-cash-multiple"
                  dense
                  required
                  flat
                />
              </v-col>
              <v-col cols="4">
                <v-text-field
                  variant="outlined"
                  :rules="[validateNumberInput]"
                  v-model="formData.end_knet"
                  label="Knet Balance"
                  prepend-inner-icon="mdi mdi-credit-card-outline"
                  dense
                  required
                  type="number"
                />
              </v-col>
            </v-row>
          </v-card-text>
          <v-card-actions class="d-flex justify-center">
            <v-btn
              :loading="loading"
              variant="flat"
              color="primary"
              size="x-large"
              class="text-uppercase"
              width="300"
              :disabled="isConfirmDisabled"
              type="submit"
            >
              Confirm & Logout
            </v-btn>
            <v-btn
              variant="flat"
              color="grey-lighten-3"
              size="x-large"
              class="text-uppercase"
              width="200"
              type="button"
              @click="cancel"
            >
              Cancel
            </v-btn>
          </v-card-actions>
        </div>
      </v-form>
    </v-card>
  </v-bottom-sheet>
</template>
<style scoped></style>
```

## File: src/components/customs/customBtn.vue
```vue
<template>
  <v-btn :color="color" :variant="variant" height="55" class="px-0">
    <div>
      <v-icon size="x-large">{{ icon }}</v-icon>
      <p class="text-uppercase font-bold mt-1" style="font-size: 0.6em">
        {{ useI18n().t(title) }}
      </p>
    </div>
  </v-btn>
</template>
⋮----
<v-icon size="x-large">{{ icon }}</v-icon>
⋮----
{{ useI18n().t(title) }}
⋮----
<script>
import { useI18n } from 'vue-i18n';
export default {
  methods: { useI18n },
  props: {
    color: String,
    variant: String,
    icon: String,
    title: String,
  },
};
</script>
<style></style>
```

## File: src/components/customs/customCard.vue
```vue
<template>
  <v-card
    variant="flat"
    density="compact"
    class="d-flex flex-column"
    :style="{ height: height }"
  >
    <template #title>
      <div class="d-flex justify-space-between">
        <div class="d-flex align-center text-uppercase panel-subheading">
          <slot name="icon">
            <img :src="icon" alt="icon-set" v-if="img" width="20" />
            <v-icon size="medium" v-else>{{ icon }}</v-icon>
          </slot>
          {{ useI18n().t(title) }}
        </div>
        <slot name="actions" />
      </div>
      <div class="dashed-hr" style="width: 100%" />
    </template>
    <template #text>
      <slot name="body"></slot>
    </template>
  </v-card>
</template>
⋮----
<template #title>
      <div class="d-flex justify-space-between">
        <div class="d-flex align-center text-uppercase panel-subheading">
          <slot name="icon">
            <img :src="icon" alt="icon-set" v-if="img" width="20" />
            <v-icon size="medium" v-else>{{ icon }}</v-icon>
          </slot>
          {{ useI18n().t(title) }}
        </div>
        <slot name="actions" />
      </div>
      <div class="dashed-hr" style="width: 100%" />
    </template>
⋮----
<v-icon size="medium" v-else>{{ icon }}</v-icon>
⋮----
{{ useI18n().t(title) }}
⋮----
<template #text>
      <slot name="body"></slot>
    </template>
⋮----
<script>
import { useI18n } from 'vue-i18n';
export default {
  methods: { useI18n },
  props: {
    title: String,
    icon: String,
    img: {
      type: Boolean,
      default: false,
    },
    height: {
      type: String,
      default: '175px',
    },
  },
};
</script>
```

## File: src/components/customs/customReceipt.vue
```vue
<script setup lang="ts">
import { formatPrice } from '../../../../../libs/utils/src/lib/formatters';
import { useI18n } from 'vue-i18n';
import { toFloat, toFloor } from '@trolley/utils';
defineProps({
  receipt: Object,
});
</script>
<template>
  <div id="invoice-POS">
    <div id="mid">
      <table class="table">
        <thead>
          <tr>
            <th class="text-body-2 font-weight-bold">Date</th>
            <th class="text-body-2 font-weight-bold">ID</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="text-body-2">{{ receipt?.created_at }}</td>
            <td class="text-body-2">{{ receipt?.unique_code }}</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div id="bot">
      <div id="table">
        <table>
          <tr class="tabletitle">
            <td class="item" style="width: 65%"><h3>Item</h3></td>
            <td class="Hours text-center" style="width: 15%"><h3>Qty</h3></td>
            <td class="Rate text-center"><h3>Sub Total</h3></td>
          </tr>
          <tr class="service" v-for="item in receipt?.items" :key="item.id">
            <td class="tableitem">
              <p class="itemtext">{{ item.name }}</p>
            </td>
            <td class="tableitem text-center">
              <p class="itemtext">{{ item.quantity }}
                <span v-if="item.is_weighted">
              {{ useI18n().t('kg') }}
              </span>
              </p>
            </td>
            <td class="tableitem text-center">
              <p class="itemtext">
                {{ item.is_weighted ? toFloor(item.quantity * item.price).toFixed(3) : toFloat(item.quantity * item.price).toFixed(3)
                }}
              </p>
            </td>
          </tr>
          <tr class="tabletitle">
            <td></td>
            <td class="Rate"><h3>Subtotal</h3></td>
            <td class="payment text-center">
              <h3>{{ formatPrice(receipt?.amount) }}</h3>
            </td>
          </tr>
        </table>
      </div>
      <div id="legalcopy">
        <p class="legal text-center">
          <strong>Thank you for Shopping at Trolley!</strong>
          <br />
          For queries or feedback: info@trolley.com.kw <br />
          Follow us on Instagram @trolley_kw <br />
          Visit our website: www.trolley.com.kw <br />
          Call 1811117
        </p>
      </div>
    </div>
  </div>
</template>
⋮----
<td class="text-body-2">{{ receipt?.created_at }}</td>
<td class="text-body-2">{{ receipt?.unique_code }}</td>
⋮----
<p class="itemtext">{{ item.name }}</p>
⋮----
<p class="itemtext">{{ item.quantity }}
⋮----
{{ useI18n().t('kg') }}
⋮----
{{ item.is_weighted ? toFloor(item.quantity * item.price).toFixed(3) : toFloat(item.quantity * item.price).toFixed(3)
                }}
⋮----
<h3>{{ formatPrice(receipt?.amount) }}</h3>
⋮----
<style scoped>
#invoice-POS {
  padding: 2mm;
  margin: 0 auto;
  width: 100%;
  background: #fff;
}
#invoice-POS ::selection {
  background: #f31544;
  color: #fff;
}
#invoice-POS ::moz-selection {
  background: #f31544;
  color: #fff;
}
#invoice-POS h1 {
  font-size: 1.5em;
  color: #222;
}
#invoice-POS h2 {
  font-size: 0.9em;
}
#invoice-POS h3 {
  font-size: 1.2em;
  font-weight: bold;
  line-height: 2em;
}
#invoice-POS p {
  font-size: 0.7em;
  color: #666;
  line-height: 1.2em;
}
#invoice-POS #top,
#invoice-POS #mid,
#invoice-POS #bot {
  border-bottom: 1px solid #eee;
}
#invoice-POS #top {
  min-height: 100px;
}
#invoice-POS #mid {
  min-height: 65px;
}
#invoice-POS #bot {
  min-height: 50px;
}
#invoice-POS #top .logo {
  height: 60px;
  width: 60px;
  background: url(http:
  background-size: 60px 60px;
}
#invoice-POS .clientlogo {
  float: left;
  height: 60px;
  width: 60px;
  background: url(http:
  background-size: 60px 60px;
  border-radius: 50px;
}
#invoice-POS .info {
  display: block;
  margin-left: 0;
}
#invoice-POS .title {
  float: right;
}
#invoice-POS .title p {
  text-align: right;
}
#invoice-POS table {
  width: 100%;
  border-collapse: collapse;
}
#invoice-POS .tabletitle {
  font-size: 0.5em;
  background: #eee;
}
#invoice-POS .service {
  border-bottom: 1px solid #eee;
}
#invoice-POS .item {
  width: 24mm;
}
#invoice-POS .itemtext {
  font-size: 0.65em;
  padding-block: 0.5em;
}
#invoice-POS #legalcopy {
  margin-top: 5mm;
  display: none;
}
</style>
```

## File: src/components/customs/emptyScreen.vue
```vue
<script lang="ts">
import { defineComponent } from 'vue';
import { useI18n } from 'vue-i18n';
export default defineComponent({
  name: 'emptyScreen',
  methods: { useI18n },
  computed: {
    products() {
      return 'EMPTY SCREEN';
    },
  },
});
</script>
<template>
  <v-card class="empty-cart-options mt-2 elevation-0 default-height-employee">
    <v-icon color="inputColor">mdi mdi-cart-plus</v-icon>
    <p class="text text-inputColor">
      {{ useI18n().t('start_adding_products') }}
    </p>
  </v-card>
</template>
⋮----
{{ useI18n().t('start_adding_products') }}
⋮----
<style scoped>
.empty-cart-options {
  background: #e0e0e0 0% 0% no-repeat padding-box;
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.default-height-employee {
  height: calc(100dvh - 325px);
}
</style>
```

## File: src/components/customs/kpiCard.vue
```vue
<script lang="ts" setup>
const props = defineProps({
  items: {
    type: Array,
    default: () => [],
  },
});
</script>
<template>
    <v-sheet class="d-flex flex-wrap mt-2">
      <div
        v-for="item in items"
        :key="item.id"
        class="flex-0-1 mb-2"
        :style="{'height': item.height + 'px', 'width': item.width + '%' }"
      >
        <div class="box">
          <p class="box-title">{{item.title}}</p>
          <p class="box-value text-primary">{{item.value}}</p>
        </div>
      </div>
    </v-sheet>
</template>
⋮----
<p class="box-title">{{item.title}}</p>
<p class="box-value text-primary">{{item.value}}</p>
⋮----
<style scoped>
.box {
  height: 80px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border: 1px dashed #adadad;
  border-radius: 8px;
  margin-inline-end: 5px;
}
.box-title {
  font-size: 12px;
  font-weight: 600;
  text-transform: uppercase;
}
.box-value {
  font-size: 32px;
  font-weight: bold;
}
</style>
```

## File: src/components/customs/sectionTitle.vue
```vue
<script setup lang="ts">
const props = defineProps<{
  title: string;
  icon: string;
}>();
</script>
<template>
  <div class="d-flex mt-3 align-center mb-2">
    <i class="text-primary" :class="icon" />
    <h4 class="mr-2" style="min-width: 100px; font-weight: 500">
      {{ title }}
    </h4>
    <div class="dashed-hr ms-1 mt-1 flex-grow-1" />
  </div>
</template>
⋮----
{{ title }}
⋮----
<style scoped>
i {
  font-size: 22px;
  color: #000;
  margin-right: 5px;
}
</style>
```

## File: src/components/dialogs/cart/cart-suspend-dialog.vue
```vue
<template>
  <BaseDialog
    v-model="dialogVisible"
    :title="t('suspend?')"
    :text="t('suspend_text')"
    :on-close="() => (dialogVisible = false)"
  >
    <div class="d-flex mt-5 justify-center">
      <v-btn
        v-for="action in actions"
        :key="action.text"
        @click="action.handler"
        class="me-5 w-25"
        :aria-label="action.text"
        color="weakTextColor"
        variant="outlined"
        >{{ action.text }}
      </v-btn>
    </div>
  </BaseDialog>
</template>
⋮----
>{{ action.text }}
⋮----
<script setup lang="ts">
import { ref } from 'vue';
import BaseDialog from '../base-dialog.vue';
import { publish, subscribe } from '@enegix/events';
import {
  EMPLOYEE_REQUESTS,
  SHOW_SUSPEND_DIALOG,
} from '../../../features/usecases/employee/events';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { useI18n } from 'vue-i18n';
import { toast } from 'vue3-toastify';
const { t } = useI18n();
const dialogVisible = ref(false);
const actions = [
  {
    text: 'Suspend',
    handler: () => {
      usePendingTransactionStore().suspend();
      publish(EMPLOYEE_REQUESTS.STASH_SALE);
      toast.success('Transaction suspended successfully');
      dialogVisible.value = false;
    },
  },
  {
    text: 'Cancel',
    handler: () => {
      dialogVisible.value = false;
    },
  },
];
subscribe(SHOW_SUSPEND_DIALOG, () => {
  dialogVisible.value = true;
});
</script>
```

## File: src/components/dialogs/base-dialog.vue
```vue
<template>
  <v-dialog
    @close="onClose"
    @click:outside="onClose"
    id="suspendDialog"
    :width="dialogWidth"
    :height="dialogHeight"
    :persistent="persistent"
  >
    <v-card
      id="suspendCard"
      :style="cardStyle"
      style="overflow: visible; border-radius: 10px"
    >
      <template #title>
        <div
          :style="headerStyle"
          class="bg-primary d-flex justify-center align-center cardTitle"
        >
          <template v-if="headerText">
            <p class="text-center" style="font-size: 20px; font-weight: bold">
              {{ headerText }}
            </p>
          </template>
          <template v-else>
            <img
              v-if="img"
              :src="img"
              style="position: absolute; bottom: 0; width: 120px"
            />
            <dialogHeader v-else style="position: absolute; bottom: 0" />
          </template>
          <div v-if="onClose">
            <v-btn
              variant="text"
              icon="mdi mdi-close-circle"
              style="position: absolute; top: 0; right: 0"
              @click="onClose"
            />
          </div>
        </div>
      </template>
      <template v-if="title || text" #text>
        <div
          :style="{ backgroundColor: contentBgColor }"
          class="pt-6 dialog-contents"
        >
          <p
            v-if="title"
            class="text-primary text-center mb-2"
            style="font-size: 20px; font-weight: bold"
          >
            {{ title }}
          </p>
          <p
            v-if="text"
            style="font-size: 16px; font-weight: normal"
            class="text-weakTextColor text-center"
          >
            {{ text }}
          </p>
        </div>
      </template>
      <template #default>
        <div :style="{ backgroundColor: contentBgColor }" class="pa-6 pt-0">
          <slot></slot>
        </div>
      </template>
    </v-card>
  </v-dialog>
</template>
⋮----
<template #title>
        <div
          :style="headerStyle"
          class="bg-primary d-flex justify-center align-center cardTitle"
        >
          <template v-if="headerText">
            <p class="text-center" style="font-size: 20px; font-weight: bold">
              {{ headerText }}
            </p>
          </template>
          <template v-else>
            <img
              v-if="img"
              :src="img"
              style="position: absolute; bottom: 0; width: 120px"
            />
            <dialogHeader v-else style="position: absolute; bottom: 0" />
          </template>
          <div v-if="onClose">
            <v-btn
              variant="text"
              icon="mdi mdi-close-circle"
              style="position: absolute; top: 0; right: 0"
              @click="onClose"
            />
          </div>
        </div>
      </template>
⋮----
<template v-if="headerText">
            <p class="text-center" style="font-size: 20px; font-weight: bold">
              {{ headerText }}
            </p>
          </template>
⋮----
{{ headerText }}
⋮----
<template v-else>
            <img
              v-if="img"
              :src="img"
              style="position: absolute; bottom: 0; width: 120px"
            />
            <dialogHeader v-else style="position: absolute; bottom: 0" />
          </template>
⋮----
<template v-if="title || text" #text>
        <div
          :style="{ backgroundColor: contentBgColor }"
          class="pt-6 dialog-contents"
        >
          <p
            v-if="title"
            class="text-primary text-center mb-2"
            style="font-size: 20px; font-weight: bold"
          >
            {{ title }}
          </p>
          <p
            v-if="text"
            style="font-size: 16px; font-weight: normal"
            class="text-weakTextColor text-center"
          >
            {{ text }}
          </p>
        </div>
      </template>
⋮----
{{ title }}
⋮----
{{ text }}
⋮----
<template #default>
        <div :style="{ backgroundColor: contentBgColor }" class="pa-6 pt-0">
          <slot></slot>
        </div>
      </template>
⋮----
<script setup lang="ts">
import dialogHeader from '../../assets/icons/dialogHeader.svg';
import { computed } from 'vue';
const props = defineProps<{
  title?: string;
  headerText?: string;
  text?: string;
  size?: string;
  contentBgColor?: string;
  onClose?: () => void;
  persistent?: boolean;
  img?: string;
}>();
const dialogWidth = computed(() => (props.size === 'large' ? '90vw' : 'auto'));
const dialogHeight = computed(() => (props.size === 'large' ? '90vh' : 'auto'));
const cardStyle = computed(() =>
  props.size === 'large' ? 'max-width: none; max-height: none;' : '',
);
const contentBgColor = computed(() => props.contentBgColor || '#ffffff');
const headerStyle = computed(() => ({
  minHeight: '100px',
  width: '100%',
  position: 'relative',
  borderRadius: '10px 10px 0 0',
  height: props.size === 'large' ? 'auto' : '100px',
}));
const handleKeydown = (event: KeyboardEvent) => {
  if (event.key === 'Escape') {
    props.onClose?.();
  }
};
</script>
<style scoped>
.dialog-contents {
  max-width: 650px;
  margin: auto;
}
.text-primary {
  color: #ffffff;
}
.text-weakTextColor {
  color: #757575;
}
.cardTitle {
  height: 60px !important;
  min-height: 60px !important;
}
</style>
```

## File: src/components/dialogs/declined-order-dialog.vue
```vue
<script setup lang="ts">
import BaseDialog from './base-dialog.vue';
import { onMounted, ref } from 'vue';
import { publish } from '@enegix/events';
import { EMPLOYEE_REQUESTS } from '../../features/usecases/employee/events';
import { dialogTopic } from './events';
import DeclineReceipt from '../../features/printing/receipts/decline-receipt.vue';
const focusPrintButton = () => {
  const printButton = document.getElementById('printButton');
  if (printButton) {
    printButton.focus();
  }
};
const dialogVisible = ref(false);
dialogTopic.subscribe('SHOW_DECLINED_ORDER_DIALOG', () => {
  dialogVisible.value = true;
});
const printReceipt = () => {
  publish(EMPLOYEE_REQUESTS.PRINT_DECLINED_RECEIPT);
  dialogVisible.value = false;
};
onMounted(() => {
  window.addEventListener('keydown', () => {
    focusPrintButton();
  });
  window.addEventListener('click', () => {
    focusPrintButton();
  });
});
</script>
<template>
  <base-dialog persistent v-model="dialogVisible" header-text="Declined Order">
    <div class="receipt-container">
      <decline-receipt class="mt-3" />
    </div>
    <v-btn
      ref="printButton"
      id="printButton"
      @click="printReceipt"
      color="primary"
      class="mt-6 w-100"
    >
      Print
    </v-btn>
  </base-dialog>
</template>
<style scoped>
.receipt-container {
  max-height: 60vh;
  overflow-y: auto;
}
</style>
```

## File: src/components/dialogs/dialog-manager.vue
```vue
<template style="z-index: 100">
  <cart-suspend-dialog />
  <cart-void-dialog />
  <product-name />
  <vcs-dialog />
  <template v-if="!isClientHomePage">
    <declined-order-dialog />
    <version-update-dialog v-if="showVersionUpdateDialog" />
    <reinstall-auth-dialog />
    <reinstall-process-dialog />
  </template>
</template>
⋮----
<template v-if="!isClientHomePage">
    <declined-order-dialog />
    <version-update-dialog v-if="showVersionUpdateDialog" />
    <reinstall-auth-dialog />
    <reinstall-process-dialog />
  </template>
⋮----
<script setup lang="ts">
import CartVoidDialog from '../../features/void-reasons/cart-void-dialog.vue';
import CartSuspendDialog from './cart/cart-suspend-dialog.vue';
import ProductName from './product-name.vue';
import { isClientHomePage } from '../../utils/path';
import VcsDialog from './vcs-dialog.vue';
import VersionUpdateDialog from '../../modules/settings/version-update-dialog.vue';
import { showVersionUpdateDialog } from '../../modules/settings/version-update';
import DeclinedOrderDialog from './declined-order-dialog.vue';
import ReinstallAuthDialog from '../../features/reinstall/reinstall-auth-dialog.vue';
import ReinstallProcessDialog from '../../features/reinstall/reinstall-process-dialog.vue';
</script>
```

## File: src/components/dialogs/events.ts
```typescript
import { Topic } from '@enegix/events';
export type DialogTopic = {
  SHOW_DECLINED_ORDER_DIALOG: void;
  SHOW_VCS_DIALOG: void;
};
```

## File: src/components/dialogs/product-name.vue
```vue
<script setup lang="ts">
import { ref } from 'vue';
import { publish, subscribe } from '@enegix/events';
import placeholderLogo from '../../assets/images/placeholder-logo.jpg?url';
import { formatPrice } from '../../../../../libs/utils/src/lib/formatters';
import type { IProduct } from '@trolley/types';
import { useI18n } from 'vue-i18n';
import { useSettings } from '../../modules/settings/store';
const { t, locale } = useI18n();
const dialogVisible = ref(false);
const product = ref(<IProduct>{});
subscribe('open-product-search-dialog', (result) => {
  dialogVisible.value = true;
  product.value = result as IProduct;
  publish('clear-search-input');
});
</script>
<template>
  <v-dialog v-model="dialogVisible" width="400">
    <v-card class="pb-15">
      <v-card-title class="d-flex justify-space-between align-center">
        <div class="text-h5 text-medium-emphasis ps-2"></div>
        <v-btn
          icon="mdi-close"
          density="compact"
          color="primary"
          style="border-radius: 100%"
          @click="dialogVisible = false"
        ></v-btn>
      </v-card-title>
      <v-card-text>
        <v-img :src="useSettings()?.settings?.logo" width="100%" />
        <div class="text-center">
          <h4 class="text-primary">{{ product.name }}</h4>
          <p class="text-h6 mt-2">
            {{ t('KD') }} {{ formatPrice(product.price) }}
          </p>
        </div>
      </v-card-text>
    </v-card>
  </v-dialog>
</template>
⋮----
<h4 class="text-primary">{{ product.name }}</h4>
⋮----
{{ t('KD') }} {{ formatPrice(product.price) }}
```

## File: src/components/dialogs/vcs-dialog.vue
```vue
<script setup lang="ts">
import BaseDialog from './base-dialog.vue';
import { ref } from 'vue';
import { dialogTopic } from './events';
import { LAST_COMMIT_HASH, TERMINAL_ID } from '../../env';
import { publish } from '@enegix/events';
import { BackendStatusTopic } from '../../features/app-mode/backend-status-topic';
const dialogVisible = ref(false);
const packageVersion = import.meta.env.PACKAGE_VERSION;
const branchName = import.meta.env.BRANCH_NAME;
const buildDate = import.meta.env.BUILD_DATE;
const formattedBuildDate = new Date(buildDate).toLocaleString();
const lastCommitHash = LAST_COMMIT_HASH;
const lastCommitMessage = import.meta.env.LAST_COMMIT_MESSAGE;
const disabled = ref(true);
dialogTopic.subscribe('SHOW_VCS_DIALOG', () => {
  dialogVisible.value = true;
  BackendStatusTopic.publish('CHECK');
  BackendStatusTopic.subscribe('STATUS', (mode) => {
    disabled.value = mode === 'OFFLINE';
  });
});
const closeDialog = () => {
  dialogVisible.value = false;
  disabled.value = true;
};
function openReInstallDialog() {
  publish('SHOW_REINSTALL_AUTH_DIALOG');
  closeDialog();
}
</script>
<template>
  <base-dialog v-model="dialogVisible" header-text="Environment Information">
    <div class="info-container mt-6">
      <p><strong>Branch Name:</strong> {{ branchName }}</p>
      <p><strong>Build Date:</strong> {{ formattedBuildDate }}</p>
      <p><strong>Last Commit Hash:</strong> {{ lastCommitHash }}</p>
      <p><strong>Terminal ID: </strong> {{ TERMINAL_ID }}</p>
    </div>
    <v-container class="mt-6 pa-0" fluid>
      <v-row dense>
        <v-col cols="6">
          <v-btn
            :disabled="disabled"
            block
            color="weakTextColor"
            @click="openReInstallDialog()"
          >
            Reinstall
          </v-btn>
        </v-col>
        <v-col cols="6">
          <v-btn block color="primary" @click="closeDialog"> Close </v-btn>
        </v-col>
      </v-row>
    </v-container>
  </base-dialog>
</template>
⋮----
<p><strong>Branch Name:</strong> {{ branchName }}</p>
<p><strong>Build Date:</strong> {{ formattedBuildDate }}</p>
<p><strong>Last Commit Hash:</strong> {{ lastCommitHash }}</p>
<p><strong>Terminal ID: </strong> {{ TERMINAL_ID }}</p>
⋮----
<style scoped>
.info-container {
  max-height: 60vh;
  overflow-y: auto;
}
</style>
```

## File: src/components/mainScreen/header-section/headerSection.vue
```vue
<template>
  <div class="d-flex justify-space-between align-top mb-3 pos-header">
    <div v-if="isClient" class="me-6 pos-logo">
      <AppLogo />
    </div>
    <v-card
      height="55px"
      color="transparent"
      class="d-flex justify-space-between ga-2"
      id="header-info"
      :class="{ employeeOptions: !isClient, clientOptions: isClient }"
    >
      <IconData
        v-for="info in headerInfo"
        :key="info.title"
        :icon="info.icon"
        :title="info.title"
        :superTitle="info.superTitle"
      />
      <IconData
        v-if="isClient"
        :title="user?.warehouse || 'N/A'"
        :icon="mapSvg"
        super-title="location"
      />
      <clock />
    </v-card>
    <search-product v-if="!isClient" />
  </div>
</template>
<script setup lang="ts">
import moment from 'moment';
import { useI18n } from 'vue-i18n';
import AppLogo from '../../appLogo.vue';
import { capitalize, computed, reactive, ref } from 'vue';
import SearchProduct from './search-product.vue';
import { auth } from '../../../modules/auth';
import officeManSvg from '../../../assets/icons/group.svg?url';
import calendarSvg from '../../../assets/icons/schedule-s.svg?url';
import mapSvg from '../../../assets/icons/map.svg?url';
import IconData from '../../iconData.vue';
import Clock from '../../workers/clock/clock.vue';
const user = auth().state.auth;
const currentDate = ref(new Date());
setInterval(() => {
  currentDate.value = new Date();
}, 1000);
const formattedDate = computed(() =>
  moment(currentDate.value).format('DD MMM, YYYY'),
);
const { isClient } = defineProps<{
  isClient: boolean;
}>();
const { t } = useI18n();
const headerInfo = reactive([
  {
    icon: officeManSvg,
    superTitle: isClient ? t('cashier') : t('welcome'),
    title: capitalize(user.value?.name || 'POS User'),
  },
  {
    icon: calendarSvg,
    superTitle: t('today_date'),
    title: formattedDate.value,
  },
]);
</script>
<style scoped>
.employeeOptions {
  width: 65%;
  margin-inline-end: 15px;
}
.clientOptions {
  width: 78%;
}
.pos-header .pos-logo {
  width: 100px;
  max-height: 55px;
  display: flex;
  align-items: end;
}
.pos-header .pos-logo img {
  object-fit: contain;
  display: block;
  width: auto;
  max-width: 100px;
}
@media screen and (min-width: 1200px) {
  .employeeOptions {
    width: 60%;
  }
  .clientOptions {
    width: 65%;
  }
  .pos-header .pos-logo {
    width: 200px;
    max-height: 60px;
    display: flex;
    align-items: end;
  }
  .pos-header .pos-logo img {
    object-fit: contain;
    display: block;
    width: auto;
  }
}
</style>
```

## File: src/components/mainScreen/header-section/search-product.vue
```vue
<script setup lang="ts">
import { ref, watch } from 'vue';
import { debouncer } from '../../../utils/debouncer';
import { trolleyClient } from '@trolley/api-sdk';
import { publish, subscribe } from '@enegix/events';
import { useI18n } from 'vue-i18n';
const { t, locale } = useI18n();
const input = ref(null);
watch(
  input,
  debouncer(() => {
    input.value &&
      trolleyClient.items
        .getApiPosItemById({
          id: input.value,
        })
        .then((res) => {
          if (res.data) publish('open-product-search-dialog', res.data);
        });
  }),
);
subscribe('clear-search-input', () => {
  input.value = null;
});
</script>
<template>
  <v-text-field
    v-model="input"
    prepend-inner-icon="mdi mdi-barcode"
    :label="t('search_for_product')"
    flat
    variant="solo"
  />
</template>
```

## File: src/components/mainScreen/bottom-cards.vue
```vue
<script setup lang="ts">
import { computed, ref } from 'vue';
import { subscribe } from '@enegix/events';
import { useLoyaltyStore } from '../../modules/loyalty/store/loyalty-store';
const props = defineProps<{
  store: {
    totalItems: number;
    subTotal: string;
    discount: string;
    redeemed: string;
    totalDue: string;
  };
}>();
const loading = ref(false);
subscribe('applying-coupon', () => {
  loading.value = true;
});
subscribe('coupon-applied', () => {
  loading.value = false;
});
const computedValues = computed(() =>
  [
    {
      label: 'items',
      amount: props.store.totalItems,
      isVisible: true,
    },
    {
      label: 'subtotal',
      amount: props.store.subTotal,
      isVisible: true,
    },
    {
      label: 'discount',
      amount: props.store.discount,
      isVisible: true,
    },
    {
      label: 'redeemed',
      amount: props.store.redeemed,
      isVisible: useLoyaltyStore().is_loyalty_enabled,
    },
    {
      label: 'total due',
      amount: props.store.totalDue,
      isVisible: true,
    },
  ].filter((item) => item.isVisible),
);
</script>
<template>
  <div style="width: 100%">
    <div class="dashed-hr mt-3" style="width: 100%" />
    <div class="d-flex mt-2">
      <div
        v-for="item in computedValues"
        :key="item.label"
        class="box flex-grow-1"
        id="total_items"
      >
        <p class="box-title">{{ item.label }}</p>
        <p
          :class="{ 'fade-out': loading }"
          style="transition: opacity 0.3s"
          class="box-value text-primary"
        >
          {{ item.amount }}
        </p>
      </div>
    </div>
  </div>
</template>
⋮----
<p class="box-title">{{ item.label }}</p>
⋮----
{{ item.amount }}
⋮----
<style scoped>
.box {
  height: 80px;
  width: 98px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border: 1px dashed #adadad;
  border-radius: 8px;
  margin-inline-end: 5px;
}
.box-title {
  font-size: 12px;
  font-weight: 600;
  text-transform: uppercase;
}
.box-value {
  font-size: 24px;
  font-weight: bold;
}
.fade-out {
  opacity: 0.5;
}
</style>
```

## File: src/components/mainScreen/categoriesCarousel.vue
```vue
<template>
  <div v-dragscroll class="d-flex container-options">
    <template v-if="!useQuickList().loading">
      <v-card
        v-for="(category, index) in useQuickList().categories"
        :key="index"
        class="rounded-pill d-flex align-center pa-1 elevation-0 category-card"
        :class="{
          'text-primary border border-primary':
            useQuickList().selectedCategory?.id === category.id,
        }"
        @click="useQuickList().select(category.id)"
      >
        <div
          class="d-flex align-center justify-center"
          style="width: 26px; height: 26px; border-radius: 50%"
          :class="{
            'bg-primary': useQuickList().selectedCategory?.id === category.id,
            'bg-background':
              useQuickList().selectedCategory?.id !== category.id,
          }"
        >
          <p style="font-size: 10px">
            {{
              locale === 'en'
                ? getInitials(category.name)
                : getInitials(category.name_ar)
            }}
          </p>
        </div>
        <p class="text">
          {{ locale === 'en' ? category.name : category.name_ar }}
        </p>
      </v-card>
    </template>
    <template v-else>
      <v-skeleton-loader
        v-for="i in 10"
        :key="i"
        type="chip"
        max-height="34px"
        min-width="100px"
        class="me-2 mb-2 rounded-pill"
      />
    </template>
  </div>
</template>
⋮----
<template v-if="!useQuickList().loading">
      <v-card
        v-for="(category, index) in useQuickList().categories"
        :key="index"
        class="rounded-pill d-flex align-center pa-1 elevation-0 category-card"
        :class="{
          'text-primary border border-primary':
            useQuickList().selectedCategory?.id === category.id,
        }"
        @click="useQuickList().select(category.id)"
      >
        <div
          class="d-flex align-center justify-center"
          style="width: 26px; height: 26px; border-radius: 50%"
          :class="{
            'bg-primary': useQuickList().selectedCategory?.id === category.id,
            'bg-background':
              useQuickList().selectedCategory?.id !== category.id,
          }"
        >
          <p style="font-size: 10px">
            {{
              locale === 'en'
                ? getInitials(category.name)
                : getInitials(category.name_ar)
            }}
          </p>
        </div>
        <p class="text">
          {{ locale === 'en' ? category.name : category.name_ar }}
        </p>
      </v-card>
    </template>
⋮----
{{
              locale === 'en'
                ? getInitials(category.name)
                : getInitials(category.name_ar)
            }}
⋮----
{{ locale === 'en' ? category.name : category.name_ar }}
⋮----
<template v-else>
      <v-skeleton-loader
        v-for="i in 10"
        :key="i"
        type="chip"
        max-height="34px"
        min-width="100px"
        class="me-2 mb-2 rounded-pill"
      />
    </template>
⋮----
<script setup lang="ts">
import { onMounted } from 'vue';
import { useQuickList } from '../../modules/quick-list/store';
import { useI18n } from 'vue-i18n';
const locale = useI18n().locale;
const getInitials = (name: string) => {
  return name
    .split(' ')
    .map((word) => word.charAt(0))
    .join('');
};
onMounted(async () => useQuickList().fetch());
</script>
<style scoped>
.text {
  font-size: 13px;
  font-weight: 500;
  flex-grow: 1;
  text-align: center;
  text-wrap: nowrap;
  padding-inline: 5px;
}
.container-options {
  overflow-x: auto;
  overflow-y: hidden;
  scrollbar-width: none;
  -ms-overflow-style: none;
  cursor: grab;
  user-select: none;
}
.container-options::-webkit-scrollbar {
  display: none;
}
.category-card {
  min-width: 90px;
  margin-inline-end: 8px;
  margin-bottom: 10px;
}
</style>
```

## File: src/components/workers/clock/clock.vue
```vue
<template>
  <div id="welcome" class="d-flex flex-row justify-center align-center">
    <img alt="icon" :src="clockSvg" width="25" />
    <div class="ml-2">
      <p class="text-caption text-primary">{{ t('time') }}</p>
      <p class="main-text">{{ currentTime }}</p>
    </div>
  </div>
</template>
⋮----
<p class="text-caption text-primary">{{ t('time') }}</p>
<p class="main-text">{{ currentTime }}</p>
⋮----
<script setup lang="ts">
import { onMounted, onUnmounted, ref } from 'vue';
import clockSvg from '../../../assets/icons/clock-square.svg?url';
import { useI18n } from 'vue-i18n';
const currentTime = ref('Loading time...');
let worker;
onMounted(() => {
  if (typeof Worker !== 'undefined') {
    worker = new Worker(new URL('./timeWorker.ts', import.meta.url), {
      type: 'module',
    });
    worker.onmessage = (event) => {
      currentTime.value = event.data;
    };
    worker.onerror = (error) => {
      console.error('Time Worker error:', error);
    };
  } else {
    console.log('Your browser does not support Web Workers.');
  }
});
const { t, locale } = useI18n();
onUnmounted(() => {
  if (worker) {
    worker.terminate();
  }
});
</script>
<style scoped>
.main-text {
  margin-top: -5px;
  font-weight: 500;
  font-size: 13px;
}
@media screen and (min-width: 1200px) {
  .main-text {
    font-size: 16px;
  }
  img {
    width: 30px;
  }
}
</style>
```

## File: src/components/workers/clock/timeWorker.ts
```typescript
import moment from "moment";
function sendTime()
```

## File: src/components/appliedCoupons.vue
```vue
<script setup lang="ts">
import { coupons } from '../store/coupons';
import CustomCard from './customs/customCard.vue';
import VourcherSvg from '../assets/icons/voucher.svg?url';
import { COUPON_TAB, globalStore } from '../store/global';
import { onMounted, ref } from 'vue';
import { BackendStatusTopic } from '../features/app-mode/backend-status-topic';
import { useCoupons } from '../store/coupons/state';
import { useI18n } from 'vue-i18n';
import CompareArrows from '../modules/loyalty/assets/compare-arrows.vue';
import { formatPrice } from '../../../../libs/utils';
import { usePendingTransactionStore } from '../../../../libs/transactions/src/hooks/vue';
const selectedCoupon = coupons().state.selectedCoupon;
const disabled = ref(true);
const t = useI18n().t;
onMounted(() => {
  BackendStatusTopic.publish('CHECK');
  BackendStatusTopic.subscribe('STATUS', (mode) => {
    disabled.value = mode === 'OFFLINE';
  });
});
</script>
<template>
  <custom-card title="applied_coupons" :img="true" height="95px">
    <template #icon>
      <img :src="VourcherSvg" alt="loyalty card" width="20" />
    </template>
    <template #actions>
      <v-btn
        :disabled="disabled"
        append-icon="mdi mdi-chevron-right"
        variant="plain"
        color="primary"
        class="text-uppercase font-weight-bold pr-0"
        :style="{ opacity: disabled ? 0.5 : 1 }"
        @click="globalStore.tab = COUPON_TAB"
      >
        Select Coupon
      </v-btn>
    </template>
    <template #body>
      <div class="bg-grey-lighten-4 rounded-lg pa-2" v-if="!selectedCoupon">
        <v-progress-circular
          v-if="useCoupons().isApplyingCoupon"
          indeterminate
          color="primary"
          size="32"
          class="mx-auto d-block"
        />
        <p v-else class="text-center text-grey pa-2">No Coupons Applied Yet</p>
      </div>
      <div v-else>
        <div class="d-flex justify-space-between bg-grey-lighten-4 rounded-lg">
          <div class="d-flex flex-row align-center ga-3 pl-1">
            <span class="coupon-value">
              {{
                formatPrice(
                  usePendingTransactionStore().itemsManager.totalActiveDiscount,
                ) + t('KD')
              }}
            </span>
            <span class="coupon-code">{{ selectedCoupon.code }}</span>
            <div class="compare-icon">
              <compare-arrows />
            </div>
            <span class="font-weight-bold">
              {{ selectedCoupon.value
              }}{{ selectedCoupon.type === 0 ? '%' : t('KD') }}
            </span>
          </div>
          <v-btn
            icon="mdi-trash-can-outline"
            color="error"
            variant="plain"
            class="opacity-100"
            @click="useCoupons().unSelectCoupon"
          />
        </div>
      </div>
    </template>
  </custom-card>
</template>
⋮----
<template #icon>
      <img :src="VourcherSvg" alt="loyalty card" width="20" />
    </template>
<template #actions>
      <v-btn
        :disabled="disabled"
        append-icon="mdi mdi-chevron-right"
        variant="plain"
        color="primary"
        class="text-uppercase font-weight-bold pr-0"
        :style="{ opacity: disabled ? 0.5 : 1 }"
        @click="globalStore.tab = COUPON_TAB"
      >
        Select Coupon
      </v-btn>
    </template>
<template #body>
      <div class="bg-grey-lighten-4 rounded-lg pa-2" v-if="!selectedCoupon">
        <v-progress-circular
          v-if="useCoupons().isApplyingCoupon"
          indeterminate
          color="primary"
          size="32"
          class="mx-auto d-block"
        />
        <p v-else class="text-center text-grey pa-2">No Coupons Applied Yet</p>
      </div>
      <div v-else>
        <div class="d-flex justify-space-between bg-grey-lighten-4 rounded-lg">
          <div class="d-flex flex-row align-center ga-3 pl-1">
            <span class="coupon-value">
              {{
                formatPrice(
                  usePendingTransactionStore().itemsManager.totalActiveDiscount,
                ) + t('KD')
              }}
            </span>
            <span class="coupon-code">{{ selectedCoupon.code }}</span>
            <div class="compare-icon">
              <compare-arrows />
            </div>
            <span class="font-weight-bold">
              {{ selectedCoupon.value
              }}{{ selectedCoupon.type === 0 ? '%' : t('KD') }}
            </span>
          </div>
          <v-btn
            icon="mdi-trash-can-outline"
            color="error"
            variant="plain"
            class="opacity-100"
            @click="useCoupons().unSelectCoupon"
          />
        </div>
      </div>
    </template>
⋮----
{{
                formatPrice(
                  usePendingTransactionStore().itemsManager.totalActiveDiscount,
                ) + t('KD')
              }}
⋮----
<span class="coupon-code">{{ selectedCoupon.code }}</span>
⋮----
{{ selectedCoupon.value
              }}{{ selectedCoupon.type === 0 ? '%' : t('KD') }}
⋮----
}}{{ selectedCoupon.type === 0 ? '%' : t('KD') }}
⋮----
<style lang="scss" scoped>
.trash-btn {
  border-top-left-radius: 45% !important;
  border-bottom-left-radius: 45% !important;
  position: relative;
}
.coupon-value {
  background-color: rgb(var(--v-theme-secondary));
  font-weight: bold;
  padding: 10px;
  border-radius: 7px;
  color: rgb(var(--v-theme-primary));
  font-size: 16px;
}
.compare-icon {
  width: 20px;
}
</style>
```

## File: src/components/appLogo.vue
```vue
<script setup lang="ts">
import { useSettings } from '../modules/settings/store';
</script>
<template>
  <img
    :src="useSettings()?.settings?.logo"
    alt="Logo"
    class="me-2"
    width="100%"
    height="100%"
  />
</template>
```

## File: src/components/calculator.vue
```vue
<script setup lang="ts">
import { ref } from 'vue';
import { globalStore } from '../store/global';
const screen = ref<string>('0');
const answer = ref<string>('0');
const expression = ref<string>('');
function append(num: string) {
  if (num === '%') {
    // Transform the last number in the expression to a percentage
    expression.value = expression.value.replace(
      /(\d+\.?\d*)$/,
      (match) => `${parseFloat(match) / 100}`,
    );
  } else {
    expression.value += num;
  }
  screen.value = expression.value;
}
function clear() {
  expression.value = '';
  screen.value = '0';
  answer.value = '0';
}
function sign() {
  expression.value =
    expression.value[0] === '-'
      ? expression.value.slice(1)
      : '-' + expression.value;
  screen.value = expression.value;
}
function calculate() {
  try {
    const sanitizedExpression = expression.value
      .replace(/÷/g, '/')
      .replace(/×/g, '*');
    const result = eval(sanitizedExpression);
    screen.value = result.toString();
    answer.value = result.toString();
    expression.value = result.toString();
  } catch (error) {
    screen.value = 'Error';
    expression.value = ''; // Reset expression on error
  }
}
</script>
<template>
  <div class="container" v-if="globalStore.showCalculator">
    <div class="calculator">
      <div class="controls">
        <span @click="globalStore.showCalculator = false">
          <v-icon icon="mdi mdi-close" />
        </span>
      </div>
      <div class="answer">{{ answer }}</div>
      <div class="display">{{ screen }}</div>
      <v-btn height="50" @click="clear" id="clear" class="btn operator"
        >C</v-btn
      >
      <v-btn height="50" @click="sign" id="sign" class="btn operator"
        >+/-</v-btn
      >
      <v-btn height="50" @click="append('%')" id="percent" class="btn operator"
        >%</v-btn
      >
      <v-btn height="50" @click="append('÷')" id="divide" class="btn operator"
        >÷</v-btn
      >
      <v-btn height="50" @click="append('7')" id="n7" class="btn">7</v-btn>
      <v-btn height="50" @click="append('8')" id="n8" class="btn">8</v-btn>
      <v-btn height="50" @click="append('9')" id="n9" class="btn">9</v-btn>
      <v-btn height="50" @click="append('*')" id="times" class="btn operator"
        >x</v-btn
      >
      <v-btn height="50" @click="append('4')" id="n4" class="btn">4</v-btn>
      <v-btn height="50" @click="append('5')" id="n5" class="btn">5</v-btn>
      <v-btn height="50" @click="append('6')" id="n6" class="btn">6</v-btn>
      <v-btn height="50" @click="append('-')" id="minus" class="btn operator"
        >-</v-btn
      >
      <v-btn height="50" @click="append('1')" id="n1" class="btn">1</v-btn>
      <v-btn height="50" @click="append('2')" id="n2" class="btn">2</v-btn>
      <v-btn height="50" @click="append('3')" id="n3" class="btn">3</v-btn>
      <v-btn height="50" @click="append('+')" id="plus" class="btn operator"
        >+</v-btn
      >
      <v-btn height="50" @click="append('0')" id="n0" class="zero">0</v-btn>
      <v-btn height="50" @click="append('.')" id="dot" class="btn">.</v-btn>
      <v-btn height="50" @click="calculate" id="equal" class="btn operator"
        >=</v-btn
      >
    </div>
  </div>
</template>
⋮----
<div class="answer">{{ answer }}</div>
<div class="display">{{ screen }}</div>
⋮----
<style scoped>
.calculator {
  position: fixed;
  top: 20%;
  left: 70px;
  display: grid;
  grid-template-rows: repeat(7, minmax(50px, auto));
  grid-template-columns: repeat(4, 61px);
  grid-gap: 6px;
  padding: 35px;
  background-color: #ffffff;
  border-radius: 10px;
  box-shadow: 0px 3px 20px rgb(17 17 17 / 20%);
}
.controls {
  display: block;
  width: 100%;
  position: absolute;
  padding: 10px;
  text-align: right;
  font-size: 12px;
}
.controls span {
  padding: 5px;
  background: #f7f7f7;
  border-radius: 50%;
  height: 30px;
  width: 30px;
  display: inline-block;
  text-align: center;
  cursor: pointer;
}
.btn,
.zero {
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  text-align: center;
  text-decoration: none;
  outline: none;
  color: #000000;
  background-color: #ececec;
  border-radius: 5px;
}
.display {
  grid-column: 1 / 5;
  display: flex;
  align-items: center;
  font-size: 18px;
  color: #a3a3a3;
  border-bottom: 1px solid #e1e1e1;
  overflow: hidden;
  text-overflow: clip;
  height: 60px;
  margin-bottom: 15px;
}
.operator {
  background-color: #fdeae4;
  color: #e74e0e;
}
.answer {
  font-weight: 500;
  color: #e74e0e;
  font-size: 55px;
  height: 65px;
  display: flex;
  grid-column: 1 / 5;
  max-width: 100%;
  overflow: hidden;
}
.zero {
  grid-column: 1 / 3;
}
</style>
```

## File: src/components/cartPreview.vue
```vue
<template>
  <v-sheet class="pa-3 items-wrapper" color="grey-lighten-3" rounded="lg">
    <data-placeholder
      v-if="!useStashedTransactionsStore().selectedStashedTransaction"
      :text="t('select_cart')"
      bg="bg-grey-lighten-3"
    />
    <v-card
      class="pa-2 d-flex flex-row mb-2"
      v-for="item in selectedStash?.itemsManager.strategy.items"
      :key="item.id"
    >
      <div
        class="w-100 d-flex justify-space-between align-center position-relative"
      >
        <div id="details" style="width: 85%">
          <p style="font-size: 11px; font-weight: 500" class="truncate">
            {{ item.name }}
          </p>
          <p style="font-size: 8px" class="text-primary">
            {{ formatPrice(item.price) }} {{ t('KD') }}
          </p>
        </div>
        <div class="text-body-2">
          <v-badge color="primary" :content="item.quantity" inline></v-badge>
        </div>
      </div>
    </v-card>
  </v-sheet>
  <v-sheet class="d-flex flex-wrap mt-2">
    <div class="flex-1-1 mb-2" style="height: 80px">
      <div class="box">
        <p class="box-title">{{ t('total_items') }}</p>
        <p class="box-value text-primary">
          {{ selectedStash?.itemsManager.totalItems || 0 }}
        </p>
      </div>
    </div>
    <div class="flex-1-1 mb-2" style="height: 80px">
      <div class="box">
        <p class="box-title">{{ t('subtotal') }}</p>
        <p class="box-value text-primary">
          {{ formatPrice(selectedStash?.itemsManager.subTotal || 0) }}
        </p>
      </div>
    </div>
    <div class="flex-1-1 mb-2" style="height: 80px">
      <div class="box">
        <p class="box-title">{{ t('total_discount') }}</p>
        <p class="box-value text-primary">
          {{ formatPrice(selectedStash?.itemsManager.totalDiscount || 0) }}
        </p>
      </div>
    </div>
    <div class="flex-1-1-100" style="height: 80px; width: 50%">
      <div class="box">
        <p class="box-title">{{ t('total_due') }}</p>
        <p class="box-value text-primary">
          {{ formatPrice(selectedStash?.itemsManager.totalDue || 0) }}
        </p>
      </div>
    </div>
    <v-btn
      class="mt-2 text-uppercase flex-1-1-100"
      aria-label="retrieve"
      block
      size="large"
      color="primary"
      :disabled="!selectedStash"
      @click="selectedStash && retrieveTransaction(selectedStash.id)"
    >
      {{ t('retrieve') }}
    </v-btn>
  </v-sheet>
</template>
⋮----
{{ item.name }}
⋮----
{{ formatPrice(item.price) }} {{ t('KD') }}
⋮----
<p class="box-title">{{ t('total_items') }}</p>
⋮----
{{ selectedStash?.itemsManager.totalItems || 0 }}
⋮----
<p class="box-title">{{ t('subtotal') }}</p>
⋮----
{{ formatPrice(selectedStash?.itemsManager.subTotal || 0) }}
⋮----
<p class="box-title">{{ t('total_discount') }}</p>
⋮----
{{ formatPrice(selectedStash?.itemsManager.totalDiscount || 0) }}
⋮----
<p class="box-title">{{ t('total_due') }}</p>
⋮----
{{ formatPrice(selectedStash?.itemsManager.totalDue || 0) }}
⋮----
{{ t('retrieve') }}
⋮----
<script setup lang="ts">
import { formatPrice } from '@trolley/utils';
import DataPlaceholder from './dataPlaceholder.vue';
import { computed } from 'vue';
import { useI18n } from 'vue-i18n';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { useStashedTransactionsStore } from '../store/stashed-transactions';
import router from '../router';
import { toast } from 'vue3-toastify';
const retrieveTransaction = (stashId: number) => {
  if (usePendingTransactionStore().itemsManager.totalItems > 0) {
    toast.error(
      'You have an active sale, please complete it before retrieving a stashed sale.',
    );
    return;
  }
  router.push({ name: 'cartPage' }).then(async () => {
    usePendingTransactionStore().resume(stashId);
    toast.success('Transaction retrieved successfully');
  });
};
const selectedStash = computed(
  () => useStashedTransactionsStore().selectedStashedTransaction,
);
const { t } = useI18n();
</script>
<style scoped>
.items-wrapper {
  height: calc(100dvh - 300px);
  overflow-y: scroll;
}
.box {
  height: 80px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  border: 1px dashed #adadad;
  border-radius: 8px;
  margin-inline-end: 5px;
}
.box-title {
  font-size: 12px;
  font-weight: 600;
  text-transform: uppercase;
}
.box-value {
  font-size: 32px;
  font-weight: bold;
}
</style>
```

## File: src/components/cartProductCard.vue
```vue
<script setup lang="ts">
import { formatPrice } from '@trolley/utils';
import { Item } from '@trolley/items';
import { useI18n } from 'vue-i18n';
import { useSettings } from '../modules/settings/store';
import { computed } from 'vue';
const { product, isClient } = defineProps<{
  product: Item;
  selectProduct: (product: Item) => void;
  increaseQuantity: (id: number) => void;
  unSelectProduct: (id: number, isAll?: boolean) => void;
  decreaseQuantity: (id: number) => void;
  isClient: boolean;
  isDisabled: boolean;
}>();
const { t, locale } = useI18n();
const item = computed(() => new Item(product, product.targetUpc));
const formatPercent = (value: number) => {
  return value.toFixed(2);
};
</script>
<template>
  <v-card class="product-options my-2 elevation-0">
    <div id="product-details" class="d-flex align-center" style="width: 40%">
      <img
        :src="useSettings()?.settings?.logo"
        width="34"
        height="34"
        style="border-radius: 8px; object-fit: contain"
        alt="product Cart"
      />
      <div id="product-details-text" class="ms-2" style="overflow: hidden">
        <p class="product-title">
          {{ locale === 'en' ? product.name : product.name_ar }}
        </p>
        <p class="text-inputColor normal-text">
          {{ t('barcode') }}: {{ product.upc }}
        </p>
      </div>
    </div>
    <div
      class="text text-inputColor ms-auto"
      style="min-width: 54px; max-width: 54px"
    >
      <div>{{ formatPrice(product.price) }} {{ t('KD') }}</div>
      <span
        v-if="product.price_before_offer"
        style="text-decoration: line-through"
      >
        {{ formatPrice(product.price_before_offer) }}
      </span>
      <span v-if="product.discount">
        [{{ formatPercent(product.discount) }}%]
      </span>
    </div>
    <div
      id="counter"
      class="d-flex align-center ms-auto"
      style="min-width: 75px; max-width: 75px"
      v-if="!isClient"
    >
      <v-btn
        variant="text"
        color="primary"
        class="counter-btn-options"
        @click="decreaseQuantity(product.id)"
        :disabled="isDisabled || !product.canBeDecreased || !product.isEditable"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="32"
          height="32"
          viewBox="0 0 32 32"
        >
          <path
            fill="currentColor"
            d="M16 4c6.6 0 12 5.4 12 12s-5.4 12-12 12S4 22.6 4 16S9.4 4 16 4m0-2C8.3 2 2 8.3 2 16s6.3 14 14 14s14-6.3 14-14S23.7 2 16 2"
          />
          <path fill="currentColor" d="M8 15h16v2H8z" />
        </svg>
      </v-btn>
      <Transition name="quantity-change">
        <p
          class="mx-auto text"
          id="quantity"
          style="color: #adadad"
          :key="product.quantity"
        >
          {{ product.quantity }}
        </p>
      </Transition>
      <v-btn
        variant="text"
        color="primary"
        class="counter-btn-options"
        @click="increaseQuantity(product.id)"
        :disabled="isDisabled || !product.canBeIncreased || !product.isEditable"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="32"
          height="32"
          viewBox="0 0 32 32"
        >
          <path
            fill="currentColor"
            d="M16 4c6.6 0 12 5.4 12 12s-5.4 12-12 12S4 22.6 4 16S9.4 4 16 4m0-2C8.3 2 2 8.3 2 16s6.3 14 14 14s14-6.3 14-14S23.7 2 16 2"
          />
          <path fill="currentColor" d="M24 15h-7V8h-2v7H8v2h7v7h2v-7h7z" />
        </svg>
      </v-btn>
    </div>
    <div
      v-else
      class="d-flex align-center justify-space-between ms-auto"
      style="min-width: 60px; max-width: 60px"
    >
      <v-icon color="primary" size="small" style="scale: 0.6"
        >mdi mdi-multiplication
      </v-icon>
      <Transition name="quantity-change">
        <p
          class="mx-auto text"
          id="quantity"
          style="color: #adadad"
          :key="product.quantity"
        >
          {{ product.quantity }}
        </p>
      </Transition>
    </div>
    <p class="text ms-4 product-price-total" id="total">
      {{ item?.getFormattedPrice() }}
      {{ t('KD') }}
    </p>
    <v-btn
      v-if="!isClient"
      class="ms-auto"
      variant="text"
      color="#D80C0C"
      @click="unSelectProduct(product.id)"
      :disabled="isDisabled || !product.isEditable"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="25"
        height="25"
        viewBox="0 0 32 32"
      >
        <path fill="currentColor" d="M12 12h2v12h-2zm6 0h2v12h-2z" />
        <path
          fill="currentColor"
          d="M4 6v2h2v20a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V8h2V6zm4 22V8h16v20zm4-26h8v2h-8z"
        />
      </svg>
    </v-btn>
  </v-card>
</template>
⋮----
{{ locale === 'en' ? product.name : product.name_ar }}
⋮----
{{ t('barcode') }}: {{ product.upc }}
⋮----
<div>{{ formatPrice(product.price) }} {{ t('KD') }}</div>
⋮----
{{ formatPrice(product.price_before_offer) }}
⋮----
[{{ formatPercent(product.discount) }}%]
⋮----
{{ product.quantity }}
⋮----
{{ product.quantity }}
⋮----
{{ item?.getFormattedPrice() }}
{{ t('KD') }}
⋮----
<style lang="scss" scoped>
.text {
  font-size: 12px;
  font-weight: normal;
}
.normal-text {
  font-size: 10px;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}
.product-options {
  display: flex;
  align-items: center;
  width: 100%;
  height: 50px;
  margin-inline-start: 2px;
  padding: 5px;
  background-color: white;
  border-radius: 10px;
}
.product-title {
  font-weight: 500;
  font-size: 12px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
.counter-btn-options {
  width: 25px !important;
  height: 30px !important;
  min-width: 16px !important;
  min-height: 16px !important;
  padding: 0 !important;
}
.counter-btn-options svg {
  width: 22px;
}
.product-price-total {
  font-weight: bold;
  color: black;
  min-width: 58px;
  max-width: 58px;
}
@keyframes pulse {
  0% {
    transform: scale(1);
    color: #adadad;
  }
  50% {
    transform: scale(1.2);
    color: rgb(var(--v-theme-primary));
  }
  100% {
    transform: scale(1);
    color: #adadad;
  }
}
.quantity-change-enter-active {
  animation: pulse 0.3s ease-out;
}
</style>
```

## File: src/components/changeLangDemo.vue
```vue
<template>
  <v-btn
    icon="mdi mdi-translate-variant"
    @click="changeLanguage"
    class="float"
    color="primary"
    label="demo"
  ></v-btn>
</template>
<script>
export default {
  methods: {
    changeLanguage() {
      const lang = this.$i18n.locale;
      console.log(lang);
      if (lang == "ar") {
        this.$i18n.locale = "en";
        localStorage.setItem("lang", "en");
      } else {
        this.$i18n.locale = "ar";
        localStorage.setItem("lang", "ar");
      }
    },
  },
};
</script>
<style scoped>
.float {
  position: fixed;
  display: none;
  bottom: 250px;
  right: 20px;
  z-index: 999;
}
</style>
```

## File: src/components/couponItem.vue
```vue
<template>
  <div
    class="coupon mt-3"
    @click="$emit('coupon', item)"
    style="cursor: pointer"
  >
    <div class="discount-value">
      <p>{{ item.discount_text }}</p>
    </div>
    <div class="expire-date bg-background">
      <p style="font-size: 8px; font-weight: normal" class="text-weakTextColor">
        {{ t('valid_until') }}
      </p>
      <p style="font-size: 10px; font-weight: normal">{{ item.end_date }}</p>
      <v-icon color="weakTextColor" size="x-large" class="mx-auto w-100"
        >mdi mdi-barcode</v-icon
      >
    </div>
  </div>
</template>
⋮----
<p>{{ item.discount_text }}</p>
⋮----
{{ t('valid_until') }}
⋮----
<p style="font-size: 10px; font-weight: normal">{{ item.end_date }}</p>
⋮----
<script>
export default {
  props: {
    item: {
      type: Object,
      required: true,
    },
  },
  emits: ['coupon'],
};
</script>
<style scoped>
.coupon {
  width: calc(33.33% - 15px);
  height: 115px;
  position: relative;
  margin-inline-end: 10px;
}
.coupon::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  background-color: white;
  width: 10px;
  height: 10px;
  border-bottom-right-radius: 70%;
}
.coupon::after {
  content: '';
  position: absolute;
  top: 0;
  right: 0;
  background-color: white;
  width: 10px;
  height: 10px;
  border-bottom-left-radius: 70%;
}
.coupon .discount-value {
  height: 40px;
  background-color: var(--secondary);
  display: flex;
  justify-content: center;
  align-items: center;
}
.coupon .expire-date::after {
  content: '';
  position: absolute;
  bottom: 0;
  right: 0;
  background-color: white;
  width: 10px;
  height: 10px;
  border-top-left-radius: 70%;
}
.coupon .expire-date::before {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  background-color: white;
  width: 10px;
  height: 10px;
  border-top-right-radius: 70%;
}
.coupon .expire-date {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: calc(115px - 40px);
}
.coupon .discount-value p {
  font-size: 16px;
  font-weight: 900;
}
</style>
```

## File: src/components/dataPlaceholder.vue
```vue
<script setup lang="ts">
import loadingSv from "../assets/images/data-bro.svg?url";
defineProps({
  text: {
    type: String,
    default: 'Loading...',
  },
  bg: {
    type: String,
    default: 'bg-grey-lighten-5',
  },
});
</script>
<template>
  <v-sheet
    class="d-flex flex-column align-center justify-center rounded-lg"
    :class="bg"
    height="100%"
  >
    <div class="w-100 text-center">
      <v-img
        class="ma-auto"
        :src="loadingSv"
        width="70%"
        height="100%"
        contain
      />
      <p class="text-caption" v-text="text"></p>
    </div>
  </v-sheet>
</template>
<style scoped>
</style>
```

## File: src/components/downloadTrolly.vue
```vue
<script setup>
import androidIcon from '../assets/images/qr-code-android.svg?url';
import iosIcon from '../assets/images/qr-code-ios.svg?url';
import { useI18n } from 'vue-i18n';
const cards = [
  {
    id: 1,
    icon: 'mdi mdi-apple',
    image: iosIcon,
  },
  {
    id: 2,
    icon: 'mdi mdi-android',
    image: androidIcon,
  },
];
const { t, locale } = useI18n();
</script>
<style scoped>
.qr-image {
  mix-blend-mode: multiply;
}
</style>
<template>
  <div class="dashed-hr w-100 mb-1" />
  <div class="d-flex justify-center mt-3">
    <v-card
      v-for="card in cards"
      :key="card.id"
      style="border-radius: 10px"
      class="me-2 bg-background w-50 px-3 py-2"
    >
      <v-card-text class="d-flex justify-space-between align-center h-100">
        <div class="right">
          <v-icon size="xx-large">{{ card.icon }}</v-icon>
          <p class="text-uppercase font-weight-bold">
            {{ t('download') }}
            {{ t('trolly') }}
          </p>
        </div>
        <img
          :src="card.image"
          alt="Download Trolley"
          width="60"
          class="qr-image"
        />
      </v-card-text>
    </v-card>
  </div>
</template>
⋮----
<v-icon size="xx-large">{{ card.icon }}</v-icon>
⋮----
{{ t('download') }}
{{ t('trolly') }}
```

## File: src/components/feedbackSlider.vue
```vue
<template>
  <customCard
    height="160px"
    title="rate_your_experience"
    class="mt-2 feedbac-slider-card"
  >
    <template #icon>
      <img :src="ratingSvg" alt="loyalty card" width="20" />
    </template>
    <template #body>
      <img :src="FeedbackSvg" style="width: 100%" alt="feedback" class="mt-2" />
      <v-slider
        :color="color"
        v-model="displayValue"
        show-ticks="always"
        track-size="12"
        step="25"
      >
      </v-slider>
    </template>
  </customCard>
</template>
⋮----
<template #icon>
      <img :src="ratingSvg" alt="loyalty card" width="20" />
    </template>
<template #body>
      <img :src="FeedbackSvg" style="width: 100%" alt="feedback" class="mt-2" />
      <v-slider
        :color="color"
        v-model="displayValue"
        show-ticks="always"
        track-size="12"
        step="25"
      >
      </v-slider>
    </template>
⋮----
<script setup lang="ts">
import { computed, onUnmounted, ref, watch } from 'vue';
import customCard from './customs/customCard.vue';
import FeedbackSvg from '../assets/icons/feedback.svg?url';
import ratingSvg from '../assets/icons/good-feedback.svg?url';
import { useCustomer } from '../store/customer/state';
const displayValue = ref(50);
const color = computed(() => {
  if (displayValue.value <= 20) return 'red';
  if (displayValue.value <= 40) return 'orange';
  if (displayValue.value <= 60) return 'yellow';
  if (displayValue.value <= 80) return 'blue';
  return 'green';
});
onUnmounted(() => {
  useCustomer().setRating(null);
});
watch(displayValue, (value) => {
  useCustomer().setRating(value);
});
</script>
<style scoped>
.v-slider.v-input--horizontal {
  margin-inline: 10%;
}
@media screen and (max-width: 1024px) {
  .feedbac-slider-card {
    height: 135px !important;
  }
}
</style>
```

## File: src/components/iconData.vue
```vue
<script setup lang="ts">
import { defineProps } from "vue";
const props = defineProps<{
  icon: string;
  title: string;
  superTitle: string;
}>();
</script>
<template>
  <div id="welcome" class="d-flex flex-row justify-center align-center">
    <img
      alt="icon"
      :src="icon"
      width="25"
    />
    <div class="ml-2">
      <p class="text-caption text-primary">{{ superTitle }}</p>
      <p class="main-text">{{ title }}</p>
    </div>
  </div>
</template>
⋮----
<p class="text-caption text-primary">{{ superTitle }}</p>
<p class="main-text">{{ title }}</p>
⋮----
<style scoped>
.main-text{
  margin-top: -5px;
  font-weight: 500;
  font-size: 13px;
}
@media screen and (min-width: 1200px){
  .main-text{
    font-size: 16px;
  }
  img{
    width: 30px;
  }
}
</style>
```

## File: src/components/loyaltyMembership.vue
```vue
<template>
  <customCard title="loyalty_membership" :img="true">
    <template #icon>
      <img :src="LoyaltyCrownSvg" alt="loyalty card" width="20" />
    </template>
    <template #body>
      <v-card
        class="bg-grey-lighten-3 pa-2 loyalty-card"
        variant="flat"
        :prepend-icon="useCustomer()?.customer?.phone ? 'mdi-account' : ''"
        :title="useCustomer()?.customer?.name"
      >
        <v-btn
          v-if="useCustomer()?.customer"
          @click="publish('remove-customer')"
          size="x-small"
          color="error"
          variant="flat"
          class="rm-loyalty"
          >Remove
        </v-btn>
        <v-sheet
          class="pa-0 mb-2 loyalty-sheet"
          width="100%"
          color="transparent"
          v-if="!useCustomer().customer"
        >
          <v-chip
            rounded="lg"
            prepend-icon="mdi mdi-barcode"
            class="w-100 pa-0 phone-chip"
            variant="text"
          >
            <template #append>
              <v-icon color="primary" @click.stop="openKeyboard">
                mdi mdi-keyboard
              </v-icon>
            </template>
            {{ t('scan_costumer_card') }}
          </v-chip>
          <v-otp-input
            variant="outlined"
            label="scan_costumer_card"
            :length="8"
            type="number"
            max-width="none"
            height="30"
            class="pa-0"
            v-model="useCustomer().customerPhone"
            @finish="fetchCustomerByPhone"
          >
          </v-otp-input>
        </v-sheet>
        <div class="d-flex justify-space-between align-center" id="card-body">
          <div id="details">
            <p class="text-primary" style="font-size: 0.7rem">
              {{ t('loyalty_points').toUpperCase() }}
            </p>
            <div class="d-flex" id="points-exchange">
              <div id="available">
                <h3>
                  {{ useCustomer()?.customer?.loyalty.pointsBalance ?? 0 }}
                </h3>
                <p style="font-size: smaller" class="text-inputColor">
                  {{ t('available') }}
                </p>
              </div>
              <div class="compare-icon">
                <compare-arrows />
              </div>
              <h3>
                {{
                  formatPrice(useCustomer()?.customer?.loyalty.pointsValue ?? 0)
                }}
                {{ t('KD') }}
              </h3>
            </div>
          </div>
          <v-btn color="#AF" variant="tonal"
            >{{ t('apply') }} [ {{ formatPrice(loyalty.$state.amount) }} ]
          </v-btn>
        </div>
        <redeem-slider
          v-if="useCustomer()?.customer"
          :points="useCustomer()?.customer?.loyalty.pointsBalance"
          :max="useCustomer()?.customer?.loyalty.pointsBalance"
        />
      </v-card>
    </template>
  </customCard>
  <Teleport to="body">
    <SimpleKeyboard
      v-model="useCustomer().customerPhone"
      @onKeyPress="onKeyPress"
      v-if="showKeyboard"
    />
  </Teleport>
</template>
⋮----
<template #icon>
      <img :src="LoyaltyCrownSvg" alt="loyalty card" width="20" />
    </template>
<template #body>
      <v-card
        class="bg-grey-lighten-3 pa-2 loyalty-card"
        variant="flat"
        :prepend-icon="useCustomer()?.customer?.phone ? 'mdi-account' : ''"
        :title="useCustomer()?.customer?.name"
      >
        <v-btn
          v-if="useCustomer()?.customer"
          @click="publish('remove-customer')"
          size="x-small"
          color="error"
          variant="flat"
          class="rm-loyalty"
          >Remove
        </v-btn>
        <v-sheet
          class="pa-0 mb-2 loyalty-sheet"
          width="100%"
          color="transparent"
          v-if="!useCustomer().customer"
        >
          <v-chip
            rounded="lg"
            prepend-icon="mdi mdi-barcode"
            class="w-100 pa-0 phone-chip"
            variant="text"
          >
            <template #append>
              <v-icon color="primary" @click.stop="openKeyboard">
                mdi mdi-keyboard
              </v-icon>
            </template>
            {{ t('scan_costumer_card') }}
          </v-chip>
          <v-otp-input
            variant="outlined"
            label="scan_costumer_card"
            :length="8"
            type="number"
            max-width="none"
            height="30"
            class="pa-0"
            v-model="useCustomer().customerPhone"
            @finish="fetchCustomerByPhone"
          >
          </v-otp-input>
        </v-sheet>
        <div class="d-flex justify-space-between align-center" id="card-body">
          <div id="details">
            <p class="text-primary" style="font-size: 0.7rem">
              {{ t('loyalty_points').toUpperCase() }}
            </p>
            <div class="d-flex" id="points-exchange">
              <div id="available">
                <h3>
                  {{ useCustomer()?.customer?.loyalty.pointsBalance ?? 0 }}
                </h3>
                <p style="font-size: smaller" class="text-inputColor">
                  {{ t('available') }}
                </p>
              </div>
              <div class="compare-icon">
                <compare-arrows />
              </div>
              <h3>
                {{
                  formatPrice(useCustomer()?.customer?.loyalty.pointsValue ?? 0)
                }}
                {{ t('KD') }}
              </h3>
            </div>
          </div>
          <v-btn color="#AF" variant="tonal"
            >{{ t('apply') }} [ {{ formatPrice(loyalty.$state.amount) }} ]
          </v-btn>
        </div>
        <redeem-slider
          v-if="useCustomer()?.customer"
          :points="useCustomer()?.customer?.loyalty.pointsBalance"
          :max="useCustomer()?.customer?.loyalty.pointsBalance"
        />
      </v-card>
    </template>
⋮----
<template #append>
              <v-icon color="primary" @click.stop="openKeyboard">
                mdi mdi-keyboard
              </v-icon>
            </template>
{{ t('scan_costumer_card') }}
⋮----
{{ t('loyalty_points').toUpperCase() }}
⋮----
{{ useCustomer()?.customer?.loyalty.pointsBalance ?? 0 }}
⋮----
{{ t('available') }}
⋮----
{{
                  formatPrice(useCustomer()?.customer?.loyalty.pointsValue ?? 0)
                }}
{{ t('KD') }}
⋮----
>{{ t('apply') }} [ {{ formatPrice(loyalty.$state.amount) }} ]
⋮----
<script setup lang="ts">
import SimpleKeyboard from '../components/simpleKeyboard.vue';
import LoyaltyCrownSvg from '../modules/loyalty/assets/crown.svg?url';
import CustomCard from './customs/customCard.vue';
import { computed, ref } from 'vue';
import RedeemSlider from './redeemSlider.vue';
import { publish } from '@enegix/events';
import { fetchCustomerDetails } from '../store/customer/actions';
import { useCustomer } from '../store/customer/state';
import { formatPrice } from '@trolley/utils';
import { useI18n } from 'vue-i18n';
import CompareArrows from '../modules/loyalty/assets/compare-arrows.vue';
import { useLoyaltyStore } from '../modules/loyalty/store/loyalty-store';
const loyalty = useLoyaltyStore();
const { t } = useI18n();
const showKeyboard = ref(false);
const customerPhone = computed(() => useCustomer().customerPhone);
const openKeyboard = () => {
  showKeyboard.value = true;
};
const onKeyPress = (button) => {
  if (button === '{downkeyboard}' || button === '{enter}') {
    fetchCustomerDetails({ phone: Number(customerPhone.value) });
    setTimeout(() => {
      showKeyboard.value = false;
    }, 200);
  }
};
const fetchCustomerByPhone = () => {
  console.log('fetching customer by phone');
  fetchCustomerDetails({ phone: Number(customerPhone.value) });
};
</script>
<style>
.loyalty-card .v-card-item {
  border-bottom: solid 1px #ccc;
  margin-bottom: 5px;
}
.loyalty-card .v-card-title {
  font-size: 1em;
  margin-bottom: 0 !important;
}
.loyalty-card .rm-loyalty {
  position: absolute;
  top: 6px;
  right: 10px;
}
.loyalty-sheet {
  margin-top: -8px;
}
.loyalty-card .v-otp-input__content {
  padding: 0 !important;
}
.phone-chip .v-chip__append {
  position: absolute;
  right: 0;
}
.compare-icon {
  width: 25px;
}
</style>
```

## File: src/components/newCoupon.vue
```vue
<script setup lang="ts">
import { coupons } from '../store/coupons';
import couponSvg from '../assets/icons/coupon-icon.svg?url';
import { useCoupons } from '../store/coupons/state';
import { useI18n } from 'vue-i18n';
import { ref } from 'vue';
import type { ICoupon } from '@trolley/types';
import CompareArrows from '../modules/loyalty/assets/compare-arrows.vue';
const props = defineProps({
  coupon: {
    type: Object as () => ICoupon,
    required: true,
  },
  readonly: Boolean,
});
const selectedCoupon = coupons().state.selectedCoupon;
const isApplyingCoupon = coupons().state.isApplyingCoupon;
const { t } = useI18n();
const loading = ref(false);
const applyCoupon = async (coupon: ICoupon) => {
  loading.value = true;
  useCoupons()
    .applyCoupon(coupon)
    .finally(() => {
      loading.value = false;
    });
};
</script>
<template>
  <div
    class="coupon-card d-flex justify-space-between rounded-lg mb-2 align-content-center align-center bg-grey-lighten-4 w-100"
    :class="{
      active: !isApplyingCoupon && selectedCoupon?.code === coupon.code,
    }"
  >
    <div class="d-flex flex-row align-center ga-3">
      <img :src="couponSvg" :alt="coupon.code" width="30" />
      <span class="coupon-code">{{ coupon.code }}</span>
      <div class="compare-icon text-primary">
        <compare-arrows />
      </div>
      <span class="coupon-value font-weight-bold"
        >{{ coupon.value }}{{ coupon.type === 0 ? '%' : t('KD') }}</span
      >
    </div>
    <v-btn
      v-if="readonly"
      :style="{
        visibility: selectedCoupon?.code === coupon.code ? 'visible' : 'hidden',
      }"
      :append-icon="'mdi mdi-check'"
      variant="text"
      color="primary"
      class="text-uppercase font-weight-bold"
    >
      {{ t('applied') }}
    </v-btn>
    <v-btn
      v-else
      :append-icon="
        selectedCoupon?.code === coupon.code
          ? 'mdi mdi-check'
          : 'mdi mdi-chevron-right'
      "
      variant="text"
      color="primary"
      class="text-uppercase font-weight-bold"
      @click="applyCoupon(coupon)"
      :disabled="isApplyingCoupon"
      :loading="loading"
    >
      {{ selectedCoupon?.code === coupon.code ? t('applied') : t('apply') }}
    </v-btn>
  </div>
</template>
⋮----
<span class="coupon-code">{{ coupon.code }}</span>
⋮----
>{{ coupon.value }}{{ coupon.type === 0 ? '%' : t('KD') }}</span
⋮----
{{ t('applied') }}
⋮----
{{ selectedCoupon?.code === coupon.code ? t('applied') : t('apply') }}
⋮----
<style lang="scss" scoped>
.coupon-card {
  padding-left: 2%;
  position: relative;
  height: 50px;
  border: solid #f5f5f5;
  transition: all 0.3s ease-in-out;
  cursor: pointer;
  &.active {
    border: solid rgb(var(--v-theme-secondary));
    background-color: rgb(var(--v-theme-secondary)) !important;
  }
}
.compare-icon {
  width: 20px;
}
</style>
```

## File: src/components/orderSummary.vue
```vue
<template>
  <customCard
    icon="mdi mdi-card-account-details"
    title="order_summary"
    height="155"
  >
    <template #icon>
      <img :src="ChoicesSvg" alt="loyalty card" width="20" />
    </template>
    <template #body>
      <v-card class="pa-3 bg-grey-lighten-3">
        <v-card-text>
          <div class="text d-flex justify-space-between mb-2">
            <p>{{ t('subtotal') }}</p>
            <p>
              {{
                formatPrice(usePendingTransactionStore().itemsManager.subTotal)
              }}
            </p>
          </div>
          <div class="text d-flex justify-space-between mb-2">
            <p>{{ t('discount') }}</p>
            <p>
              {{
                formatPrice(
                  usePendingTransactionStore().itemsManager.totalDiscount,
                )
              }}
            </p>
          </div>
          <div class="text d-flex justify-space-between mb-2">
            <p>{{ t('points_redeemed') }}</p>
            <p>{{ formatPrice(loyalty.amount) }}</p>
          </div>
          <v-divider></v-divider>
          <div class="text font-bold d-flex justify-space-between mt-2">
            <p class="font-weight-bold">{{ t('total_[KD]') }}</p>
            <p class="font-weight-bold">
              {{
                formatPrice(usePendingTransactionStore().itemsManager.totalDue)
              }}
            </p>
          </div>
        </v-card-text>
      </v-card>
    </template>
  </customCard>
</template>
⋮----
<template #icon>
      <img :src="ChoicesSvg" alt="loyalty card" width="20" />
    </template>
<template #body>
      <v-card class="pa-3 bg-grey-lighten-3">
        <v-card-text>
          <div class="text d-flex justify-space-between mb-2">
            <p>{{ t('subtotal') }}</p>
            <p>
              {{
                formatPrice(usePendingTransactionStore().itemsManager.subTotal)
              }}
            </p>
          </div>
          <div class="text d-flex justify-space-between mb-2">
            <p>{{ t('discount') }}</p>
            <p>
              {{
                formatPrice(
                  usePendingTransactionStore().itemsManager.totalDiscount,
                )
              }}
            </p>
          </div>
          <div class="text d-flex justify-space-between mb-2">
            <p>{{ t('points_redeemed') }}</p>
            <p>{{ formatPrice(loyalty.amount) }}</p>
          </div>
          <v-divider></v-divider>
          <div class="text font-bold d-flex justify-space-between mt-2">
            <p class="font-weight-bold">{{ t('total_[KD]') }}</p>
            <p class="font-weight-bold">
              {{
                formatPrice(usePendingTransactionStore().itemsManager.totalDue)
              }}
            </p>
          </div>
        </v-card-text>
      </v-card>
    </template>
⋮----
<p>{{ t('subtotal') }}</p>
⋮----
{{
                formatPrice(usePendingTransactionStore().itemsManager.subTotal)
              }}
⋮----
<p>{{ t('discount') }}</p>
⋮----
{{
                formatPrice(
                  usePendingTransactionStore().itemsManager.totalDiscount,
                )
              }}
⋮----
<p>{{ t('points_redeemed') }}</p>
<p>{{ formatPrice(loyalty.amount) }}</p>
⋮----
<p class="font-weight-bold">{{ t('total_[KD]') }}</p>
⋮----
{{
                formatPrice(usePendingTransactionStore().itemsManager.totalDue)
              }}
⋮----
<script setup lang="ts">
import { formatPrice } from '@trolley/utils';
import CustomCard from './customs/customCard.vue';
import ChoicesSvg from '../assets/icons/choices.svg?url';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { useI18n } from 'vue-i18n';
import { useLoyaltyStore } from '../modules/loyalty/store/loyalty-store';
const { t, locale } = useI18n();
const loyalty = useLoyaltyStore();
</script>
<style scoped>
.text {
  font: 14px medium;
}
.imp-text {
  font-size: 18px;
  font-weight: bold;
}
</style>
```

## File: src/components/productCardWithoutPic.vue
```vue
<template>
  <v-card-item class="product-item w-100 mb-2 bg-white">
    <div
      class="w-100 d-flex justify-space-between px-2 align-center position-relative"
    >
      <div id="details" style="width: 85%">
        <p style="font-size: 11px; font-weight: 500" class="truncate">
          {{ product.name }}
        </p>
        <p style="font-size: 8px" class="text-primary">
          {{ formatPrice(product.price) }} {{ useI18n().t('KD') }}
          <span v-if="product.quantity">
            <span class="text-inputColor mx-1"> * </span> {{ product.quantity }}
              <span v-if="product.unit">
               {{ useI18n().t(product.unit) }}
              </span>
          </span>
        </p>
      </div>
      <v-btn
        color="primary"
        variant="tonal"
        class="buy-button"
        @click="onSelect(product)"
      >
        <v-icon>mdi mdi-cart-outline</v-icon>
      </v-btn>
    </div>
  </v-card-item>
</template>
⋮----
{{ product.name }}
⋮----
{{ formatPrice(product.price) }} {{ useI18n().t('KD') }}
⋮----
<span class="text-inputColor mx-1"> * </span> {{ product.quantity }}
⋮----
{{ useI18n().t(product.unit) }}
⋮----
<script setup lang="ts">
import { formatPrice } from '@trolley/utils';
import type { IItem } from '@trolley/types';
import { useI18n } from 'vue-i18n';
const { product, onSelect } = defineProps<{
  product: IItem;
  onSelect: (item: IItem) => void;
}>();
</script>
<style scoped>
.product-item {
  border-radius: 10px;
  height: 45px;
  padding-inline: 10px !important;
  padding-inline-end: 5px !important;
}
.buy-button {
  height: 35px !important;
  width: 35px !important;
  min-width: 35px !important;
  border-radius: 10px;
}
.truncate {
  width: 100%;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
</style>
```

## File: src/components/quickActions.vue
```vue
<template>
  <customCard title="quick_actions" img>
    <template #icon>
      <img :src="DoubleTapSvg" alt="quick-actions" />
    </template>
    <template #body>
      <div class="d-flex ga-1 mb-1">
        <customBtn
          :disabled="!usePendingTransactionStore().isProcessable"
          v-for="(btn, index) in buttons"
          :aria-label="btn.title"
          :key="index"
          :title="btn.title"
          :icon="btn.icon"
          :color="btn.color"
          :variant="btn.variant"
          class="flex-grow-1"
          @click="publish(btn.action)"
        />
      </div>
      <v-btn
        :disabled="!usePendingTransactionStore().isProcessable"
        color="primary"
        size="large"
        v-if="!showConfirmButtons"
        @click="showConfirmButtons = true"
        class="w-100 text-uppercase mb-2"
        >{{ t('process_payment') }}
      </v-btn>
      <div class="w-100 d-flex ga-1" v-if="showConfirmButtons">
        <v-btn
          color="warning"
          size="large"
          class="flex-grow-1 text-uppercase mb-2"
          @click="showConfirmButtons = false"
          >{{ t('cancel') }}
        </v-btn>
        <v-btn
          :disabled="!usePendingTransactionStore().isProcessable"
          color="success"
          size="large"
          class="text-uppercase mb-2 flex-grow-1"
          @click="
            usePaymentMethods().fetchPaymentMethods();
            globalStore.tab = 'checkout';
            showConfirmButtons = false;
          "
        >
          {{ t('confirm') }}
        </v-btn>
      </div>
    </template>
  </customCard>
</template>
⋮----
<template #icon>
      <img :src="DoubleTapSvg" alt="quick-actions" />
    </template>
<template #body>
      <div class="d-flex ga-1 mb-1">
        <customBtn
          :disabled="!usePendingTransactionStore().isProcessable"
          v-for="(btn, index) in buttons"
          :aria-label="btn.title"
          :key="index"
          :title="btn.title"
          :icon="btn.icon"
          :color="btn.color"
          :variant="btn.variant"
          class="flex-grow-1"
          @click="publish(btn.action)"
        />
      </div>
      <v-btn
        :disabled="!usePendingTransactionStore().isProcessable"
        color="primary"
        size="large"
        v-if="!showConfirmButtons"
        @click="showConfirmButtons = true"
        class="w-100 text-uppercase mb-2"
        >{{ t('process_payment') }}
      </v-btn>
      <div class="w-100 d-flex ga-1" v-if="showConfirmButtons">
        <v-btn
          color="warning"
          size="large"
          class="flex-grow-1 text-uppercase mb-2"
          @click="showConfirmButtons = false"
          >{{ t('cancel') }}
        </v-btn>
        <v-btn
          :disabled="!usePendingTransactionStore().isProcessable"
          color="success"
          size="large"
          class="text-uppercase mb-2 flex-grow-1"
          @click="
            usePaymentMethods().fetchPaymentMethods();
            globalStore.tab = 'checkout';
            showConfirmButtons = false;
          "
        >
          {{ t('confirm') }}
        </v-btn>
      </div>
    </template>
⋮----
>{{ t('process_payment') }}
⋮----
>{{ t('cancel') }}
⋮----
{{ t('confirm') }}
⋮----
<script setup lang="ts">
import CustomBtn from './customs/customBtn.vue';
import CustomCard from './customs/customCard.vue';
import DoubleTapSvg from '../assets/icons/double-tap.svg?url';
import { publish, subscribe } from '@enegix/events';
import { CART_ACTIONS, SHOW_SUSPEND_DIALOG, SHOW_VOID_DIALOG } from '../features/usecases/employee/events';
import { ref } from 'vue';
import { COUPON_TAB, globalStore } from '../store/global';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { usePaymentMethods } from '../modules/payments/payments-store';
import { useI18n } from 'vue-i18n';
const showConfirmButtons = ref(false);
const { t, locale } = useI18n();
subscribe(CART_ACTIONS.SHOW_CART_COUPONS, () => {
  globalStore.tab = COUPON_TAB;
});
const buttons = [
  {
    title: 'void_sale',
    icon: 'mdi mdi-window-close',
    variant: 'tonal',
    color: 'error',
    action: SHOW_VOID_DIALOG,
  },
  {
    title: 'suspend',
    icon: 'mdi mdi-pause',
    variant: 'tonal',
    color: 'primary',
    action: SHOW_SUSPEND_DIALOG,
  },
];
</script>
```

## File: src/components/quickProductsAdd.vue
```vue
<template>
  <v-card
    id="quick-products-add"
    variant="flat"
    class="bg-grey-lighten-3 mb-3"
    :style="{
  height: props.height || `calc(100dvh - ${useLoyaltyStore().is_loyalty_enabled ? '400px' : '225px'})`,
  borderRadius: '15px',
  padding: '8px',
  position: 'relative'
}"
  >
    <div
      id="products-container"
      v-dragscroll
      class="cards-options no-text-highlight"
    >
      <div id="products" v-if="!loading">
        <productCardWithoutPic
          v-for="(product, index) in availableProducts"
          :key="index"
          :product="product"
          :on-select="onSelect"
        />
      </div>
      <div id="products-skeleton" v-else>
        <v-skeleton-loader
          v-for="i in 10"
          :key="i"
          elevation="0"
          class="mb-2 w-100"
          style="border-radius: 10px"
          max-height="45"
          height="45"
          type="text"
        ></v-skeleton-loader>
      </div>
    </div>
    <v-text-field
      v-if="props.onUPC"
      prepend-inner-icon="mdi mdi-barcode"
      :label="t('enter_product_UPC')"
      density="compact"
      flat
      hide-details
      style="position: absolute; bottom: 10px; right: 10px; left: 10px"
      v-model="UPC"
      v-on:keyup.enter="handleUPC"
    >
      <template #append-inner>
        <v-icon color="primary" @click.stop="openKeyboard"
          >mdi mdi-keyboard
        </v-icon>
      </template>
    </v-text-field>
  </v-card>
  <Teleport to="body">
    <SimpleKeyboard
      v-model="UPC"
      @onKeyPress="onKeyPress"
      v-if="showKeyboard"
    />
  </Teleport>
</template>
⋮----
<template #append-inner>
        <v-icon color="primary" @click.stop="openKeyboard"
          >mdi mdi-keyboard
        </v-icon>
      </template>
⋮----
<script setup lang="ts">
import productCardWithoutPic from './productCardWithoutPic.vue';
import SimpleKeyboard from '../components/simpleKeyboard.vue';
import { ref } from 'vue';
import type { IItem } from '@trolley/types';
import { useI18n } from 'vue-i18n';
import { useLoyaltyStore } from '../modules/loyalty/store/loyalty-store';
const { t, locale } = useI18n();
const props = defineProps<{
  loading: boolean;
  availableProducts: IItem[];
  onSelect: (item: IItem) => void;
  onUPC?: (upc: string) => void;
  height?: string;
}>();
const UPC = ref('');
const handleUPC = () => {
  if (!UPC.value) return;
  props.onUPC && props.onUPC(UPC.value);
  UPC.value = '';
};
const showKeyboard = ref(false);
const onKeyPress = (event: string) => {
  if (event === '{downkeyboard}') {
    setTimeout(() => {
      handleUPC();
      showKeyboard.value = false;
    }, 200);
  }
  if (event === '{enter}') {
    setTimeout(() => {
      handleUPC();
      showKeyboard.value = false;
    }, 200);
  }
};
const openKeyboard = () => {
  showKeyboard.value = true;
};
</script>
<style scoped>
.buy-button {
  width: 34px !important;
  height: 22px !important;
  border-radius: 9px 0px 11px 0px !important;
  position: absolute;
  bottom: 0;
  right: 0;
}
.text {
  font-weight: 600;
  font-size: 8px;
  margin-inline-start: 3%;
}
.cards-options {
  height: 88%;
  overflow-y: auto;
  overflow-x: hidden;
}
.cards-options::-webkit-scrollbar {
  display: none;
}
.skeleton-item {
  box-sizing: border-box;
  width: calc(50% - 5px);
  margin-bottom: 10px;
  border-radius: 10px;
  position: relative;
  overflow: hidden;
}
.skeleton-item:nth-child(odd) {
  margin-inline-end: 5px;
}
</style>
```

## File: src/components/redeemSlider.vue
```vue
<script setup lang="ts">
import { computed, defineProps, onMounted, ref } from 'vue';
import { BackendStatusTopic } from '../features/app-mode/backend-status-topic';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { useLoyaltyStore } from '../modules/loyalty/store/loyalty-store';
const loyalty = useLoyaltyStore();
const props = defineProps({
  min: {
    type: Number,
    default: 0,
  },
  max: {
    type: Number,
    default: 0,
  },
  value: Number,
});
const maxPoints = computed(() => {
  return Math.min(
    usePendingTransactionStore().itemsManager.redeemableAmount /
      loyalty.redeem_factor,
    props.max,
  );
});
const disabled = ref(true);
onMounted(() => {
  BackendStatusTopic.publish('CHECK');
  BackendStatusTopic.subscribe('STATUS', (mode) => {
    disabled.value = mode === 'OFFLINE';
  });
});
</script>
<template>
  <v-slider
    :disabled="disabled"
    v-model="loyalty.points"
    :max="maxPoints"
    :min
    :step="loyalty.step"
    class="align-center"
    hide-details
    color="primary"
    @end="
      usePendingTransactionStore().itemsManager.setRedeemedAmount(
        useLoyaltyStore().amount,
      )
    "
  >
  </v-slider>
</template>
```

## File: src/components/simpleKeyboard.vue
```vue
<template>
  <div :class="keyboardClass"></div>
</template>
<script>
import Keyboard from 'simple-keyboard';
import 'simple-keyboard/build/css/index.css';
export default {
  name: 'SimpleKeyboard',
  emits: ['update:modelValue', 'onKeyPress'],
  props: {
    keyboardClass: {
      default: 'simple-keyboard',
      type: String,
    },
    modelValue: {
      type: String,
      required: true,
    },
  },
  data: () => ({
    keyboard: null,
  }),
  mounted() {
    this.keyboard = new Keyboard(this.keyboardClass, {
      onChange: this.onChange,
      onKeyPress: this.onKeyPress,
      theme: 'hg-theme-default hg-theme-ios',
      layout: {
        default: [
          '1 2 3 4 5 6 7 8 9 0',
          'q w e r t y u i o p {bksp}',
          '{caps} a s d f g h j k l {enter}',
          'z x c v b n m ,',
          '{space} {downkeyboard}',
        ],
        shift: [
          '1 2 3 4 5 6 7 8 9 0',
          'Q W E R T Y U I O P {bksp}',
          '{caps} A S D F G H J K L {enter}',
          'Z X C V B N M ,',
          '{space} {downkeyboard}',
        ],
      },
      display: {
        '{caps}': '⇪',
        '{shift}': '⇧',
        '{shiftactivated}': '⇧',
        '{enter}': 'Enter',
        '{bksp}': '⌫',
        '{space}': ' space ',
        '{downkeyboard}': '🞃',
      },
    });
  },
  methods: {
    onChange(input) {
      this.$emit('update:modelValue', input);
    },
    onKeyPress(button) {
      this.$emit('onKeyPress', button);
      if (button === '{shift}') this.handleShift();
      if (button === '{caps}') this.handleCapsLock();
    },
    handleCapsLock() {
      let currentLayout = this.keyboard.options.layoutName;
      let capsToggle = currentLayout === 'default' ? 'shift' : 'default';
      this.keyboard.setOptions({
        layoutName: capsToggle,
      });
    },
    handleShift() {
      let currentLayout = this.keyboard.options.layoutName;
      let shiftToggle = currentLayout === 'default' ? 'shift' : 'default';
      this.keyboard.setOptions({
        layoutName: shiftToggle,
      });
    },
  },
  watch: {
    value(newValue) {
      this.keyboard.setInput(newValue);
    },
  },
};
</script>
<style scoped></style>
```

## File: src/components/split-payments.vue
```vue
<template>
  <custom-card
    icon="mdi mdi-card-account-details"
    title="Split Payments"
    height="155"
    class="mb-auto"
  >
    <template #icon>
      <img :src="ChoicesSvg" alt="loyalty card" width="20" />
    </template>
    <template #body>
      <div class="split-payments">
        <v-card
          v-for="payment in usePendingTransactionStore().payments"
          :key="payment.id"
          class="split-payment-card d-flex justify-space-between align-center mb-2 pa-2"
        >
          <span class="payment-method text-uppercase">
            {{ payment.readable_payment_method }}
            <span
              v-if="!isCashPaymentMethod(payment.payment_method_id)"
              class="payment-extra"
              >{{ payment.extra }}</span
            >
          </span>
          <div class="ms-auto d-flex align-center ga-1">
            <span class="payment-amount">{{
              formatPrice(payment.amount) + ' KD'
            }}</span>
            <v-btn
              variant="text"
              color="#D80C0C"
              icon="mdi mdi-trash-can-outline"
              @click="
                usePendingTransactionStore().paymentsManager.removePayment(
                  payment.key,
                )
              "
            />
          </div>
        </v-card>
        <div class="total-paid mt-4 mb-4">
          <div class="d-flex justify-space-between align-center">
            <span>Total Paid [KD]</span>
            <span class="total-amount"
              >{{
                formatPrice(
                  usePendingTransactionStore().paymentsManager.totalPaidAmount,
                )
              }}
              KD</span
            >
          </div>
        </div>
      </div>
    </template>
  </custom-card>
</template>
⋮----
<template #icon>
      <img :src="ChoicesSvg" alt="loyalty card" width="20" />
    </template>
<template #body>
      <div class="split-payments">
        <v-card
          v-for="payment in usePendingTransactionStore().payments"
          :key="payment.id"
          class="split-payment-card d-flex justify-space-between align-center mb-2 pa-2"
        >
          <span class="payment-method text-uppercase">
            {{ payment.readable_payment_method }}
            <span
              v-if="!isCashPaymentMethod(payment.payment_method_id)"
              class="payment-extra"
              >{{ payment.extra }}</span
            >
          </span>
          <div class="ms-auto d-flex align-center ga-1">
            <span class="payment-amount">{{
              formatPrice(payment.amount) + ' KD'
            }}</span>
            <v-btn
              variant="text"
              color="#D80C0C"
              icon="mdi mdi-trash-can-outline"
              @click="
                usePendingTransactionStore().paymentsManager.removePayment(
                  payment.key,
                )
              "
            />
          </div>
        </v-card>
        <div class="total-paid mt-4 mb-4">
          <div class="d-flex justify-space-between align-center">
            <span>Total Paid [KD]</span>
            <span class="total-amount"
              >{{
                formatPrice(
                  usePendingTransactionStore().paymentsManager.totalPaidAmount,
                )
              }}
              KD</span
            >
          </div>
        </div>
      </div>
    </template>
⋮----
{{ payment.readable_payment_method }}
⋮----
>{{ payment.extra }}</span
⋮----
<span class="payment-amount">{{
              formatPrice(payment.amount) + ' KD'
            }}</span>
⋮----
>{{
                formatPrice(
                  usePendingTransactionStore().paymentsManager.totalPaidAmount,
                )
              }}
⋮----
<script setup lang="ts">
import CustomCard from './customs/customCard.vue';
import ChoicesSvg from '../assets/icons/choices.svg?url';
import { formatPrice } from '../../../../libs/utils/src/lib/formatters';
import { isCashPaymentMethod } from '@trolley/knet';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
</script>
<style scoped>
.split-payment-card {
  background-color: #f5f5f5;
  border-radius: 5px;
}
.payment-method {
  font-weight: bold;
}
.payment-amount {
  font-size: 1.1rem;
  color: #000;
}
.payment-extra {
  display: block;
  font-size: 11px;
  font-weight: 100;
  color: #666666;
}
.total-paid {
  border-top: 1px solid #ddd;
  padding-top: 10px;
}
.total-amount {
  font-weight: bold;
}
</style>
```

## File: src/components/StatusIndicator.vue
```vue
<script lang="ts" setup>
import { computed, ref } from 'vue';
interface StatusIndicatorProps {
  subscribeTopic: string;
  statusEnum: Record<string, any>;
  commandsEnum: Record<string, any>;
  initialState: string;
  title: string;
  icons: Record<string, string>;
  colorMap: Record<string, string>;
  reconnectCommand: string;
  disconnectCommand: string;
}
const props = defineProps<StatusIndicatorProps>();
const connectionState = ref(props.initialState);
const statusDetails = computed(() => {
  const state = connectionState.value;
  const details = {
    color: 'weakTextColor',
    icon: props.icons[state] || 'mdi-circle',
    animationClass: 'fade-in',
  };
  if (state === props.statusEnum.CONNECTED) {
    details.color = props.colorMap.connected;
    details.icon = props.icons.connected;
  } else if (state === props.statusEnum.DISCONNECTED) {
    details.icon = props.icons.disconnected;
  } else if (state === props.statusEnum.CONNECTING) {
    details.color = props.colorMap.connecting;
    details.icon = props.icons.connecting;
    details.animationClass = 'rotate';
  }
  return details;
});
</script>
<template>
  <v-list-item
    class="d-flex flex-column justify-center align-center mt-4 transition"
    link
    :style="{ opacity: 1 }"
  >
    <template #prepend>
      <v-icon
        :color="statusDetails.color"
        :class="['ms-8', 'mdi', statusDetails.animationClass]"
      >
        {{ statusDetails.icon }}
      </v-icon>
    </template>
    <template #title>
      <p class="text-weakTextColor nav-items-title fade-in mt-1">
        {{ props.title }}
      </p>
    </template>
  </v-list-item>
  <v-divider />
</template>
⋮----
<template #prepend>
      <v-icon
        :color="statusDetails.color"
        :class="['ms-8', 'mdi', statusDetails.animationClass]"
      >
        {{ statusDetails.icon }}
      </v-icon>
    </template>
⋮----
{{ statusDetails.icon }}
⋮----
<template #title>
      <p class="text-weakTextColor nav-items-title fade-in mt-1">
        {{ props.title }}
      </p>
    </template>
⋮----
{{ props.title }}
⋮----
<style scoped>
.fade-in {
  animation: fadeIn 1s ease-in-out;
}
.rotate {
  animation: rotate 1s linear infinite;
}
@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
</style>
```

## File: src/components/transaction-subbmiting.vue
```vue
<template>
  <BaseDialog
    header-text="Processing Payment"
    persistent
    v-model="showDialog"
    :showCloseButton="false"
    :showFooter="false"
  >
    <div class="text-center">
      <transition name="fade">
        <div v-if="paymentStatus === 'processing'">
          <p class="text-gray-600 text-lg mt-4">
            Please wait while we process your payment...
          </p>
          <p class="text-primary text-xl font-semibold mt-2">
            {{ countdown }}s
          </p>
          <v-progress-circular indeterminate color="primary" class="mt-4" />
        </div>
        <div v-else-if="paymentStatus === 'success'">
          <div class="flex justify-center mb-4">
            <img alt="Payment Success" class="w-24 h-24 animate-bounce" />
          </div>
          <p class="text-green-600 text-lg font-semibold">
            Payment Successful!
          </p>
        </div>
        <div v-else-if="paymentStatus === 'declined'">
          <div class="flex justify-center mb-4">
            <img alt="Payment Declined" class="w-24 h-24 animate-bounce" />
          </div>
          <p class="text-red-600 text-lg font-semibold">Payment Declined!</p>
        </div>
      </transition>
    </div>
  </BaseDialog>
</template>
⋮----
{{ countdown }}s
⋮----
<script setup>
import { onMounted, onUnmounted, ref } from 'vue';
import BaseDialog from './dialogs/base-dialog.vue';
import { subscribe } from '@enegix/events';
import { TRANSACTION_EVENTS } from '@trolley/transactions';
import { KNET_TIMEOUT } from '@trolley/knet';
const countdown = ref(KNET_TIMEOUT / 1000);
const showDialog = ref(true);
const paymentStatus = ref('processing');
let timer = null;
const startCountdown = () => {
  countdown.value = KNET_TIMEOUT / 1000;
  paymentStatus.value = 'processing';
  timer = setInterval(() => {
    if (countdown.value > 0) {
      countdown.value--;
    } else {
      clearInterval(timer);
      showDialog.value = false;
    }
  }, 1000);
};
onMounted(() => {
  const handleBeforeUnload = (event) => {
    event.preventDefault();
    event.returnValue = '';
  };
  window.addEventListener('beforeunload', handleBeforeUnload);
  startCountdown();
  subscribe(TRANSACTION_EVENTS.PAID, () => {
    clearInterval(timer);
    setTimeout(() => {
      showDialog.value = false;
    }, 2000);
  });
  subscribe(TRANSACTION_EVENTS.FAILED, () => {
    paymentStatus.value = 'declined';
    clearInterval(timer);
    setTimeout(() => {
      showDialog.value = false;
    }, 2000);
  });
  onUnmounted(() => {
    window.removeEventListener('beforeunload', handleBeforeUnload);
  });
});
</script>
<style scoped>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s;
}
.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}
</style>
```

## File: src/components/trolleyCoupon.vue
```vue
<script setup lang="ts">
import { defineProps } from 'vue';
import couponSvg from '../assets/images/vectors/coupon-cardw.svg?url';
import type { ICoupon } from '@trolley/types';
import { useI18n } from 'vue-i18n';
const { t, locale } = useI18n();
const props = defineProps({
  coupon: {
    type: Object as () => ICoupon,
    required: true,
  },
});
</script>
<template>
  <div class="coupon-card">
    <span class="coupon-value"
      >{{ coupon.value }}{{ coupon.type === 0 ? '%' : t('KD') }}</span
    >
    <span class="coupon-code">{{ coupon.code }}</span>
    <span class="coupon-expiry">{{ coupon.end_date }}</span>
    <img :src="couponSvg" :alt="coupon.code" />
  </div>
</template>
⋮----
>{{ coupon.value }}{{ coupon.type === 0 ? '%' : t('KD') }}</span
⋮----
<span class="coupon-code">{{ coupon.code }}</span>
<span class="coupon-expiry">{{ coupon.end_date }}</span>
⋮----
<style scoped>
.coupon-card {
  flex: 1 1 50%;
  padding-inline: 1%;
  position: relative;
  height: 60px;
}
.coupon-value {
  color: #fff;
  font-weight: bold;
  position: absolute;
  left: 8%;
  top: 10%;
  font-size: 1.15em;
}
.coupon-code {
  position: absolute;
  color: #fff;
  left: 8%;
  font-size: 0.75em;
  font-weight: 500;
  bottom: 20%;
  text-transform: uppercase;
}
.coupon-expiry {
  position: absolute;
  color: #fff;
  font-size: 0.75em;
  bottom: 20%;
  right: 18%;
  font-weight: 500;
  text-transform: uppercase;
}
</style>
```

## File: src/components/updateApp.vue
```vue
<template>
  <div>
    A new update is available, please click
    <a href="#!" @click="updateApp">here</a> to apply.
  </div>
</template>
<script>
export default {
  name: 'UpdateApplication',
  props: ['closeToast', 'toastProps'],
  methods: {
    async updateApp(e) {
      this.closeToast(e);
    },
  },
};
</script>
```

## File: src/composables/cookies.js
```javascript
function setCookie(key, value, expirationDays = 1) {
return new Promise((resolve, reject) => {
⋮----
const expirationDate = new Date();
expirationDate.setDate(expirationDate.getDate() + expirationDays);
const cookieValue = `${encodeURIComponent(key)}=${encodeURIComponent(
⋮----
)}; expires=${expirationDate.toUTCString()}; path=/;`;
⋮----
resolve();
⋮----
reject(error);
⋮----
function getCookie(key) {
const cookieName = `${encodeURIComponent(key)}=`;
const cookieArray = document.cookie.split(";");
⋮----
let cookie = cookieArray[i].trim();
if (cookie.indexOf(cookieName) === 0) {
return decodeURIComponent(
cookie.substring(cookieName.length, cookie.length),
⋮----
function updateCookie(key, newValue, expirationDays = 1) {
⋮----
getCookie(key)
.then((existingValue) => {
⋮----
setCookie(key, newValue, expirationDays)
.then(() => resolve())
.catch((error) => reject(error));
⋮----
function removeCookie(key) {
⋮----
expirationDate.setTime(expirationDate.getTime() - 1);
document.cookie = `${encodeURIComponent(
⋮----
)}=; expires=${expirationDate.toUTCString()}; path=/;`;
```

## File: src/composables/prefetchMedia.ts
```typescript
interface PrefetchOptions {
  delay?: number;
  batchSize?: number;
  timeout?: number;
}
export function useMediaPrefetch()
⋮----
const fetchWithTimeout = async (url: string, timeout: number) =>
const prefetchMedia = async (
    urls: string[],
    {
      delay = 0,
      batchSize = urls.length,
      timeout = 10000
    }: PrefetchOptions = {}
): Promise<
```

## File: src/features/app-mode/backend-status-indicator.vue
```vue
<script lang="ts" setup>
import { onMounted, reactive, watch } from 'vue';
import { BACKEND_STATUS, BackendStatusTopic } from './backend-status-topic';
import { trolleyClient } from '@trolley/api-sdk';
const status = reactive({
  color: 'weakTextColor',
  icon: 'mdi-radiobox-blank',
  animationClass: 'fade-in',
  mode: BACKEND_STATUS.OFFLINE,
});
BackendStatusTopic.subscribe('STATUS', (newStatus) => {
  switch (newStatus) {
    case BACKEND_STATUS.ONLINE:
      status.color = 'primary';
      status.icon = 'mdi-radiobox-marked';
      status.mode = BACKEND_STATUS.ONLINE;
      break;
    case BACKEND_STATUS.OFFLINE:
      status.icon = 'mdi-radiobox-blank';
      status.mode = BACKEND_STATUS.OFFLINE;
      break;
  }
});
onMounted(() => {
  BackendStatusTopic.publish('CHECK');
});
watch(
  () => status.mode,
  async (newMode) => {
    if (newMode === BACKEND_STATUS.ONLINE) {
      trolleyClient.transactions.postApiPosSyncTransactions.apply(
        trolleyClient.transactions,
      );
    }
  },
  {
    deep: true,
  },
);
</script>
<template>
  <v-list-item
    class="d-flex flex-column justify-center align-center mt-4 transition"
    link
    disabled
    :style="{ opacity: 1 }"
  >
    <template #prepend>
      <v-icon
        :color="status.color"
        :class="['ms-8', 'mdi', status.animationClass]"
      >
        {{ status.icon }}
      </v-icon>
    </template>
    <template #title>
      <p class="text-weakTextColor nav-items-title fade-in mt-1">
        {{ status.mode }}
      </p>
    </template>
  </v-list-item>
  <v-divider />
</template>
⋮----
<template #prepend>
      <v-icon
        :color="status.color"
        :class="['ms-8', 'mdi', status.animationClass]"
      >
        {{ status.icon }}
      </v-icon>
    </template>
⋮----
{{ status.icon }}
⋮----
<template #title>
      <p class="text-weakTextColor nav-items-title fade-in mt-1">
        {{ status.mode }}
      </p>
    </template>
⋮----
{{ status.mode }}
⋮----
<style scoped>
.nav-items-title {
  font-size: 9px;
}
.fade-in {
  animation: fadeIn 1s ease-in-out;
}
.rotate {
  animation: rotate 1s linear infinite;
}
@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
</style>
```

## File: src/features/app-mode/backend-status-topic.ts
```typescript
import { subscribe, Topic } from '@enegix/events';
import { trolleyClient } from '@trolley/api-sdk';
export enum BACKEND_STATUS {
  ONLINE = 'ONLINE',
  OFFLINE = 'OFFLINE',
}
type AppModeTopicType = {
  STATUS: BACKEND_STATUS;
  CHECK: void;
};
⋮----
export const initAppMode = () =>
export const checkBackendHealth = () =>
export const setupAppModeWatchers = () =>
```

## File: src/features/app-mode/check.ts
```typescript
import { ref } from 'vue';
import type { HealthStatus } from '../sync-check/use-health-check';
import { BACKEND_STATUS, BackendStatusTopic } from './backend-status-topic';
export const useBackendStatusCheck = async () =>
```

## File: src/features/items/check.ts
```typescript
import { ref } from 'vue';
import type { HealthStatus } from '../sync-check/use-health-check';
import { z } from 'zod';
import { itemsStore } from './store';
import { getCachedEntity } from '@trolley/api-sdk';
⋮----
export const useItemsCheck = async () =>
```

## File: src/features/items/store.ts
```typescript
import { defineStore } from 'pinia';
import { ref } from 'vue';
import { trolleyClient } from '@trolley/api-sdk';
⋮----
const fetchAllItems = async () =>
```

## File: src/features/multi-tab/multi-tab-broadcast.ts
```typescript
import { useBroadcastChannel } from '@vueuse/core';
```

## File: src/features/multi-tab/multi-tab.vue
```vue
<template>
  <v-app>
    <v-container class="h-screen d-flex flex-column justify-center align-center max-w-md text-center">
      <v-card elevation="4" class="pa-6">
        <v-card-title>
          <span>Trolley POS cashier screen is already open in another tab!</span>
        </v-card-title>
        <v-card-text>
          <p>
            Please close this tab and return to the cashier screen which is already open.
          </p>
        </v-card-text>
      </v-card>
    </v-container>
  </v-app>
</template>
<script>
export default {};
</script>
```

## File: src/features/payment-methods/check.ts
```typescript
import { z } from 'zod';
import { ref } from 'vue';
import type { HealthStatus } from '../sync-check/use-health-check';
import { usePaymentMethods } from '../../modules/payments/payments-store';
⋮----
export const usePaymentMethodsCheck = async () =>
```

## File: src/features/printing/order/cash-section.vue
```vue
<script setup lang="ts">
import { useCurrentOrderStore } from '../state';
import { formatPrice } from '../../../../../../libs/utils/src/lib/formatters';
const { state } = useCurrentOrderStore();
const props = defineProps<{
  type: 'purchase' | 'refund';
}>();
</script>
<template>
  <tr>
    <td class="text-right font-weight-bolder">
      {{ props.type === 'refund' ? 'REFUND CASH' : 'CASH' }}
    </td>
    <td class="text-right font-weight-bolder">
      {{ formatPrice(state.computed.cash) }}
    </td>
  </tr>
  <tr v-if="state.computed.change > 0">
    <td class="text-right font-weight-bolder">
      {{ props.type === 'refund' ? 'REFUND CHANGE' : 'CHANGE' }}
    </td>
    <td class="text-right font-weight-bolder">
      {{ formatPrice(state.computed.change) }}
    </td>
  </tr>
</template>
⋮----
{{ props.type === 'refund' ? 'REFUND CASH' : 'CASH' }}
⋮----
{{ formatPrice(state.computed.cash) }}
⋮----
{{ props.type === 'refund' ? 'REFUND CHANGE' : 'CHANGE' }}
⋮----
{{ formatPrice(state.computed.change) }}
```

## File: src/features/printing/order/cashier-section.vue
```vue
<script setup lang="ts">
import { useCurrentOrderStore } from '../state';
import { useI18n } from 'vue-i18n';
const { t, locale } = useI18n();
const { state } = useCurrentOrderStore();
</script>
<template>
  <tr>
    <th>{{ t('cashier_id') }}</th>
    <td>{{ state.order?.cashier_id }}</td>
  </tr>
  <tr>
    <th>{{ t('cashier_name') }}</th>
    <td>{{ state.order?.cashier_name }}</td>
  </tr>
</template>
⋮----
<th>{{ t('cashier_id') }}</th>
<td>{{ state.order?.cashier_id }}</td>
⋮----
<th>{{ t('cashier_name') }}</th>
<td>{{ state.order?.cashier_name }}</td>
```

## File: src/features/printing/order/declined-receipt.vue
```vue
<script lang="ts" setup>
import { formatPrice } from '@trolley/utils';
import { useCurrentOrderStore } from '../state';
import KnetSection from './knet-section.vue';
import SharedSection from './shared-section.vue';
const { state } = useCurrentOrderStore();
</script>
<template>
  <div style="width: 80mm; margin: auto">
    <table id="receipt" class="mb-2">
      <thead style="display: table-row-group">
        <tr>
          <th class="text-center" colspan="2" scope="row">
            <svg
              height="64"
              viewBox="-1 -3 38 38"
              width="64"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g id="logo" transform="translate(22054.189 5267.175)">
                <path
                  id="Path_172751"
                  d="M148.65,399.871a2.523,2.523,0,1,0-2.523,2.523,2.523,2.523,0,0,0,2.523-2.523"
                  fill="#404040"
                  transform="translate(-22173.852 -5637.197)"
                />
                <path
                  id="Path_172752"
                  d="M96,399.871a2.523,2.523,0,1,0,2.523-2.523A2.523,2.523,0,0,0,96,399.871"
                  fill="#404040"
                  transform="translate(-22138.576 -5637.197)"
                />
                <path
                  id="Path_172753"
                  d="M52.1,294.809l5.467,2.264,2.54,19.289a1.835,1.835,0,0,0,1.819,1.6h19.72a1.56,1.56,0,0,0,0-3.12H63.579l-.411-3.12h18.3a1.56,1.56,0,0,0,1.441-.963L87.278,300.2a1.56,1.56,0,0,0-1.441-2.157H61.369l-.248-1.887A1.836,1.836,0,0,0,60,294.7l-6.646-2.753a1.6,1.6,0,0,0-2.079.775,1.56,1.56,0,0,0,.825,2.082m27.435,6.358h3.67L80.131,308.6H76.46Zm-7.341,0h3.67L72.79,308.6H69.12Zm-3.67,0L65.45,308.6H62.758l-.979-7.432Z"
                  fill="#404040"
                  transform="translate(-22105.33 -5559)"
                />
              </g>
            </svg>
            <p class="text-center mb-1">
              {{ state.branch?.name }}
            </p>
          </th>
        </tr>
        <tr>
          <th colspan="2">
            Quantity
            <v-icon icon="mdi-close" />
            Item
            <span class="float-right ml-auto">Unit Price</span>
          </th>
        </tr>
      </thead>
      <tbody>
        <template v-for="(item, _index) in state.order?.items" :key="_index">
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.quantity }}
              <span v-if="item.unit">
              {{item.unit}}
              </span>
              <v-icon icon="mdi-close" />
              {{ item.name }}
            </td>
            <td class="text-muted text-right align-middle" rowspan="2">
              <b>{{ formatPrice(item.price) }}</b>
            </td>
          </tr>
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.name_ar }}
            </td>
          </tr>
        </template>
      </tbody>
      <tfoot style="display: table-row-group">
        <tr>
          <td class="text-right font-weight-bolder">QUANTITY</td>
          <td class="text-right font-weight-bolder">
            {{ state.computed.quantity }}
          </td>
        </tr>
        <tr>
          <td class="text-right font-weight-bolder">SUBTOTAL</td>
          <td class="text-right font-weight-bolder">
            {{ formatPrice(state.order?.sub_total) }}
          </td>
        </tr>
        <tr v-if="state.order?.redeem_amount_points">
          <td class="text-right font-weight-bolder">Redeemed Points</td>
          <td class="text-right font-weight-bolder">
            {{ state.order?.redeem_amount_points }}
          </td>
        </tr>
        <tr v-if="state.order?.redeemed_amount">
          <td class="text-right font-weight-bolder">Redeemed Amount</td>
          <td class="text-right font-weight-bolder">
            -{{ formatPrice(state.order?.redeemed_amount) }}
          </td>
        </tr>
        <tr>
          <td class="text-right font-weight-bolder">TOTAL</td>
          <td class="text-right font-weight-bolder">
            {{ formatPrice(state.order?.amount ?? 0) }}
          </td>
        </tr>
      </tfoot>
    </table>
    <div id="declined" class="row mb-2 text-center">
      <p>DECLINED</p>
      <v-icon id="decline-icon" icon="mdi-close" size="3x" />
    </div>
    <table id="order" style="width: 80mm">
      <shared-section>
        <knet-section v-if="state.knetResponse" />
      </shared-section>
    </table>
  </div>
</template>
⋮----
{{ state.branch?.name }}
⋮----
<template v-for="(item, _index) in state.order?.items" :key="_index">
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.quantity }}
              <span v-if="item.unit">
              {{item.unit}}
              </span>
              <v-icon icon="mdi-close" />
              {{ item.name }}
            </td>
            <td class="text-muted text-right align-middle" rowspan="2">
              <b>{{ formatPrice(item.price) }}</b>
            </td>
          </tr>
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.name_ar }}
            </td>
          </tr>
        </template>
⋮----
{{ item.quantity }}
⋮----
{{item.unit}}
⋮----
{{ item.name }}
⋮----
<b>{{ formatPrice(item.price) }}</b>
⋮----
{{ item.name_ar }}
⋮----
{{ state.computed.quantity }}
⋮----
{{ formatPrice(state.order?.sub_total) }}
⋮----
{{ state.order?.redeem_amount_points }}
⋮----
-{{ formatPrice(state.order?.redeemed_amount) }}
⋮----
{{ formatPrice(state.order?.amount ?? 0) }}
⋮----
<style>
.ml-auto {
  margin-left: auto;
}
.mb-1 {
  margin-bottom: 1em;
}
.mb-2 {
  margin-bottom: 2em;
}
.float-right {
  float: right;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.font-weight-bolder {
  font-weight: bolder;
}
table {
  border-collapse: collapse;
}
th {
  text-align: left;
}
#receipt thead tr:last-child {
  border-bottom: 1px solid black !important;
}
#receipt tbody .w-80 {
  width: 80%;
}
#receipt tbody td {
  padding-top: 0.5em;
  padding-bottom: 0.5em;
}
#receipt tfoot tr:first-child {
  border-top: 1px solid black !important;
}
#transaction .row div {
  display: inline-block;
}
#transaction #declined,
#transaction #declined * {
  text-align: center;
}
#transaction #declined p {
  font-size: 1.5rem;
  font-weight: bolder;
  margin: 0 0 0.25em;
}
#receipt {
  width: 100%;
}
#order {
  margin-top: 8px;
}
#order td {
  text-align: right;
}
@page {
  margin: 0;
}
</style>
```

## File: src/features/printing/order/knet-section.vue
```vue
<script setup lang="ts">
import { useCurrentOrderStore } from '../state';
import { useI18n } from 'vue-i18n';
const { state } = useCurrentOrderStore();
const t = useI18n().t;
const cardNumber = state.order?.card_number;
const cardType = state.order?.card_name || state.knetResponse?.cardType;
const merchantId = state.order?.merchant_id;
</script>
<template>
  <tr v-if="state.order?.payment_id">
    <th scope="col">{{ t('transaction_id') }}</th>
    <td>{{ state.order?.payment_id }}</td>
  </tr>
  <tr v-if="cardNumber">
    <th scope="col">{{ t('card_number') }}</th>
    <td>{{ cardNumber }}</td>
  </tr>
  <tr v-if="cardType">
    <th scope="col">{{ t('card_type') }}</th>
    <td>{{ cardType }}</td>
  </tr>
  <tr v-if="merchantId">
    <th scope="col">{{ t('merchant_id') }}</th>
    <td>{{ merchantId }}</td>
  </tr>
</template>
⋮----
<th scope="col">{{ t('transaction_id') }}</th>
<td>{{ state.order?.payment_id }}</td>
⋮----
<th scope="col">{{ t('card_number') }}</th>
<td>{{ cardNumber }}</td>
⋮----
<th scope="col">{{ t('card_type') }}</th>
<td>{{ cardType }}</td>
⋮----
<th scope="col">{{ t('merchant_id') }}</th>
<td>{{ merchantId }}</td>
```

## File: src/features/printing/order/order-receipt.vue
```vue
<script lang="ts" setup>
import { formatPrice } from '@trolley/utils';
import { orderReceiptRef } from '../printing-feature';
import { useCurrentOrderStore } from '../state';
import KnetSection from './knet-section.vue';
import SharedSection from './shared-section.vue';
import CashSection from './cash-section.vue';
import { hasPayment } from '../helpers';
import { useCustomer } from '../../../store/customer/state';
import { PAYMENT_METHODS } from '@trolley/types';
import { isTransactionPaid } from '@trolley/transactions';
import { useI18n } from 'vue-i18n';
const { t, locale } = useI18n();
const { state } = useCurrentOrderStore();
</script>
<template>
  <div ref="orderReceiptRef" style="width: 80mm; margin: auto">
    <table id="receipt" class="mb-2">
      <thead style="display: table-row-group">
        <tr>
          <th class="text-center" colspan="2" scope="row">
            <svg
              height="64"
              viewBox="-1 -3 38 38"
              width="64"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g id="logo" transform="translate(22054.189 5267.175)">
                <path
                  id="Path_172751"
                  d="M148.65,399.871a2.523,2.523,0,1,0-2.523,2.523,2.523,2.523,0,0,0,2.523-2.523"
                  fill="#404040"
                  transform="translate(-22173.852 -5637.197)"
                />
                <path
                  id="Path_172752"
                  d="M96,399.871a2.523,2.523,0,1,0,2.523-2.523A2.523,2.523,0,0,0,96,399.871"
                  fill="#404040"
                  transform="translate(-22138.576 -5637.197)"
                />
                <path
                  id="Path_172753"
                  d="M52.1,294.809l5.467,2.264,2.54,19.289a1.835,1.835,0,0,0,1.819,1.6h19.72a1.56,1.56,0,0,0,0-3.12H63.579l-.411-3.12h18.3a1.56,1.56,0,0,0,1.441-.963L87.278,300.2a1.56,1.56,0,0,0-1.441-2.157H61.369l-.248-1.887A1.836,1.836,0,0,0,60,294.7l-6.646-2.753a1.6,1.6,0,0,0-2.079.775,1.56,1.56,0,0,0,.825,2.082m27.435,6.358h3.67L80.131,308.6H76.46Zm-7.341,0h3.67L72.79,308.6H69.12Zm-3.67,0L65.45,308.6H62.758l-.979-7.432Z"
                  fill="#404040"
                  transform="translate(-22105.33 -5559)"
                />
              </g>
            </svg>
            <p class="text-center mb-1">
              {{ state.branch?.name }}
            </p>
          </th>
        </tr>
        <tr>
          <th colspan="2">
            Quantity
            <v-icon icon="mdi-close" />
            Item
            <span class="float-right ml-auto">Unit Price</span>
          </th>
        </tr>
      </thead>
      <tbody>
        <template v-for="(item, _index) in state.order?.items" :key="_index">
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.quantity }}
              <span v-if="item.unit">
              {{item.unit}}
              </span>
              <v-icon icon="mdi-close" />
              {{ item.name }}
            </td>
            <td class="text-muted text-right align-middle" rowspan="2">
              <b>{{ formatPrice(item.price) }}</b>
            </td>
          </tr>
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.name_ar }}
            </td>
          </tr>
        </template>
      </tbody>
      <tfoot style="display: table-row-group">
        <tr>
          <td class="text-right font-weight-bolder">QUANTITY</td>
          <td class="text-right font-weight-bolder">
            {{ state.computed.quantity }}
          </td>
        </tr>
        <tr>
          <td class="text-right font-weight-bolder">SUBTOTAL</td>
          <td class="text-right font-weight-bolder">
            {{ formatPrice(state.order?.sub_total) }}
          </td>
        </tr>
        <tr v-if="state.order?.earned_points">
          <td class="text-right font-weight-bolder">Earned Points</td>
          <td class="text-right font-weight-bolder">
            {{ state.order?.earned_points }}
          </td>
        </tr>
        <tr v-if="state.order?.redeem_amount_points">
          <td class="text-right font-weight-bolder">Redeemed Points</td>
          <td class="text-right font-weight-bolder">
            {{ state.order?.redeem_amount_points }}
          </td>
        </tr>
        <tr v-if="state.order?.redeemed_amount">
          <td class="text-right font-weight-bolder">Redeemed Amount</td>
          <td class="text-right font-weight-bolder">
            -{{ formatPrice(state.order?.redeemed_amount) }}
          </td>
        </tr>
        <tr v-if="state.order?.discount_value">
          <td class="text-right font-weight-bolder">Discount</td>
          <td class="text-right font-weight-bolder">
            -{{ formatPrice(state.order?.discount_value) }}
          </td>
        </tr>
        <tr>
          <td class="text-right font-weight-bolder">TOTAL</td>
          <td class="text-right font-weight-bolder">
            {{ formatPrice(state.order?.amount ?? 0) }}
          </td>
        </tr>
        <cash-section
          type="purchase"
          v-if="
            hasPayment(state.order?.payments ?? [], PAYMENT_METHODS.CASH) &&
            state?.order?.payments.length === 1
          "
        />
      </tfoot>
    </table>
    <table id="order" style="width: 80mm">
      <tr>
        <th scope="col">{{ t('transaction_status') }}</th>
        <td>
          {{ t('approved') }}
        </td>
      </tr>
      <shared-section>
        <knet-section v-if="state.knetResponse" />
      </shared-section>
    </table>
    <p
      v-if="state.order && isTransactionPaid(state.order)"
      class="text-center font-weight-medium mt-4"
    >
      Thank You
      {{
        useCustomer()?.receiptCustomer?.name?.trim() ||
        state?.order?.customer_name
      }}
      for Shopping at Trolley.
    </p>
    <p class="text-center text-caption text--secondary mt-2 mb-2">
      Exchange & Refund in 14 Days, T&C applied
      <br />
      إستبدال السلع وإعادتها خلال 14 يوم ,تطبق الشروط والأحكام
    </p>
    <hr style="margin-top: 1em; margin-bottom: 5px" />
  </div>
</template>
⋮----
{{ state.branch?.name }}
⋮----
<template v-for="(item, _index) in state.order?.items" :key="_index">
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.quantity }}
              <span v-if="item.unit">
              {{item.unit}}
              </span>
              <v-icon icon="mdi-close" />
              {{ item.name }}
            </td>
            <td class="text-muted text-right align-middle" rowspan="2">
              <b>{{ formatPrice(item.price) }}</b>
            </td>
          </tr>
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.name_ar }}
            </td>
          </tr>
        </template>
⋮----
{{ item.quantity }}
⋮----
{{item.unit}}
⋮----
{{ item.name }}
⋮----
<b>{{ formatPrice(item.price) }}</b>
⋮----
{{ item.name_ar }}
⋮----
{{ state.computed.quantity }}
⋮----
{{ formatPrice(state.order?.sub_total) }}
⋮----
{{ state.order?.earned_points }}
⋮----
{{ state.order?.redeem_amount_points }}
⋮----
-{{ formatPrice(state.order?.redeemed_amount) }}
⋮----
-{{ formatPrice(state.order?.discount_value) }}
⋮----
{{ formatPrice(state.order?.amount ?? 0) }}
⋮----
<th scope="col">{{ t('transaction_status') }}</th>
⋮----
{{ t('approved') }}
⋮----
{{
        useCustomer()?.receiptCustomer?.name?.trim() ||
        state?.order?.customer_name
      }}
⋮----
<style>
.ml-auto {
  margin-left: auto;
}
.mb-1 {
  margin-bottom: 1em;
}
.mb-2 {
  margin-bottom: 2em;
}
.float-right {
  float: right;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.font-weight-bolder {
  font-weight: bolder;
}
table {
  border-collapse: collapse;
}
th {
  text-align: left;
}
#receipt thead tr:last-child {
  border-bottom: 1px solid black !important;
}
#receipt tbody .w-80 {
  width: 80%;
}
#receipt tbody td {
  padding-top: 0.5em;
  padding-bottom: 0.5em;
}
#receipt tfoot tr:first-child {
  border-top: 1px solid black !important;
}
#transaction .row div {
  display: inline-block;
}
#transaction #declined,
#transaction #declined * {
  text-align: center;
}
#transaction #declined p {
  font-size: 1.5rem;
  font-weight: bolder;
  margin: 0 0 0.25em;
}
#receipt {
  width: 100%;
}
#receipt *,
#transaction *,
#order *,
.thankyou {
  font-family: monospace, monospace !important;
  font-size: 13px !important;
}
#order {
  margin-top: 8px;
}
#order td {
  text-align: right;
}
@page {
  margin: 0;
}
</style>
```

## File: src/features/printing/order/refund-receipt.vue
```vue
<script lang="ts" setup>
import { formatPrice } from '@trolley/utils';
import { useCurrentOrderStore } from '../state';
import KnetSection from './knet-section.vue';
import SharedSection from './shared-section.vue';
import CashSection from './cash-section.vue';
import { useCustomer } from '../../../store/customer/state';
import { hasPayment } from '../helpers';
import { PAYMENT_METHODS } from '@trolley/types';
import { isTransactionPaid } from '@trolley/transactions';
const { state } = useCurrentOrderStore();
</script>
<template>
  <div ref="" style="width: 80mm; margin: auto">
    <table id="receipt" class="mb-2">
      <thead style="display: table-row-group">
        <tr>
          <th class="text-center" colspan="2" scope="row">
            <svg
              height="64"
              viewBox="-1 -3 38 38"
              width="64"
              xmlns="http://www.w3.org/2000/svg"
            >
              <g id="logo" transform="translate(22054.189 5267.175)">
                <path
                  id="Path_172751"
                  d="M148.65,399.871a2.523,2.523,0,1,0-2.523,2.523,2.523,2.523,0,0,0,2.523-2.523"
                  fill="#404040"
                  transform="translate(-22173.852 -5637.197)"
                />
                <path
                  id="Path_172752"
                  d="M96,399.871a2.523,2.523,0,1,0,2.523-2.523A2.523,2.523,0,0,0,96,399.871"
                  fill="#404040"
                  transform="translate(-22138.576 -5637.197)"
                />
                <path
                  id="Path_172753"
                  d="M52.1,294.809l5.467,2.264,2.54,19.289a1.835,1.835,0,0,0,1.819,1.6h19.72a1.56,1.56,0,0,0,0-3.12H63.579l-.411-3.12h18.3a1.56,1.56,0,0,0,1.441-.963L87.278,300.2a1.56,1.56,0,0,0-1.441-2.157H61.369l-.248-1.887A1.836,1.836,0,0,0,60,294.7l-6.646-2.753a1.6,1.6,0,0,0-2.079.775,1.56,1.56,0,0,0,.825,2.082m27.435,6.358h3.67L80.131,308.6H76.46Zm-7.341,0h3.67L72.79,308.6H69.12Zm-3.67,0L65.45,308.6H62.758l-.979-7.432Z"
                  fill="#404040"
                  transform="translate(-22105.33 -5559)"
                />
              </g>
            </svg>
            <p class="text-center mb-1">
              <strong class="text-center">REFUND RECEIPT</strong>
            </p>
            <p class="text-center mb-1">
              {{ state.branch?.name }}
            </p>
          </th>
        </tr>
        <tr>
          <th colspan="2">
            Quantity
            <v-icon icon="mdi-close" />
            Item
            <span class="float-right ml-auto">Unit Price</span>
          </th>
        </tr>
      </thead>
      <tbody>
        <template v-for="(item, _index) in state.order?.items" :key="_index">
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.quantity }}
              <span v-if="item.unit">
              {{item.unit}}
              </span>
              <v-icon icon="mdi-close" />
              {{ item.name }}
            </td>
            <td class="text-muted text-right align-middle" rowspan="2">
              <b>{{ formatPrice(item.price) }}</b>
            </td>
          </tr>
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.name_ar }}
            </td>
          </tr>
        </template>
      </tbody>
      <tfoot style="display: table-row-group">
        <tr>
          <td class="text-right font-weight-bolder">REFUND QUANTITY</td>
          <td class="text-right font-weight-bolder">
            {{ state.computed.quantity }}
          </td>
        </tr>
        <tr>
          <td class="text-right font-weight-bolder">REFUND SUBTOTAL</td>
          <td class="text-right font-weight-bolder">
            {{ formatPrice(state.order?.sub_total) }}
          </td>
        </tr>
        <tr v-if="state.order?.redeem_amount_points">
          <td class="text-right font-weight-bolder">REFUND Redeemed Points</td>
          <td class="text-right font-weight-bolder">
            {{ state.order?.redeem_amount_points }}
          </td>
        </tr>
        <tr v-if="state.order?.redeemed_amount">
          <td class="text-right font-weight-bolder">REFUND Redeemed Amount</td>
          <td class="text-right font-weight-bolder">
            -{{ formatPrice(state.order?.redeemed_amount) }}
          </td>
        </tr>
        <tr>
          <td class="text-right font-weight-bolder">REFUND TOTAL</td>
          <td class="text-right font-weight-bolder">
            {{ formatPrice(state.order?.amount ?? 0) }}
          </td>
        </tr>
        <cash-section
          type="refund"
          v-if="
            hasPayment(state.order?.payments ?? [], PAYMENT_METHODS.CASH) &&
            state?.order?.payments.length === 1
          "
        />
      </tfoot>
    </table>
    <table id="order" style="width: 80mm">
      <shared-section>
        <knet-section v-if="state.knetResponse" />
      </shared-section>
    </table>
    <hr style="margin-top: 1em; margin-bottom: 5px; opacity: 0" />
    <p
      v-if="state.order && isTransactionPaid(state.order)"
      class="thankyou text-center"
    >
      Thank You {{ useCustomer()?.receiptCustomer?.name?.trim() }} for Shopping
      at Trolley.
    </p>
    <hr style="margin-top: 3em; margin-bottom: 5px" />
  </div>
</template>
⋮----
{{ state.branch?.name }}
⋮----
<template v-for="(item, _index) in state.order?.items" :key="_index">
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.quantity }}
              <span v-if="item.unit">
              {{item.unit}}
              </span>
              <v-icon icon="mdi-close" />
              {{ item.name }}
            </td>
            <td class="text-muted text-right align-middle" rowspan="2">
              <b>{{ formatPrice(item.price) }}</b>
            </td>
          </tr>
          <tr>
            <td class="text-muted w-80" style="width: 78%">
              {{ item.name_ar }}
            </td>
          </tr>
        </template>
⋮----
{{ item.quantity }}
⋮----
{{item.unit}}
⋮----
{{ item.name }}
⋮----
<b>{{ formatPrice(item.price) }}</b>
⋮----
{{ item.name_ar }}
⋮----
{{ state.computed.quantity }}
⋮----
{{ formatPrice(state.order?.sub_total) }}
⋮----
{{ state.order?.redeem_amount_points }}
⋮----
-{{ formatPrice(state.order?.redeemed_amount) }}
⋮----
{{ formatPrice(state.order?.amount ?? 0) }}
⋮----
Thank You {{ useCustomer()?.receiptCustomer?.name?.trim() }} for Shopping
⋮----
<style>
.ml-auto {
  margin-left: auto;
}
.mb-1 {
  margin-bottom: 1em;
}
.mb-2 {
  margin-bottom: 2em;
}
.float-right {
  float: right;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.font-weight-bolder {
  font-weight: bolder;
}
table {
  border-collapse: collapse;
}
th {
  text-align: left;
}
#receipt thead tr:last-child {
  border-bottom: 1px solid black !important;
}
#receipt tbody .w-80 {
  width: 80%;
}
#receipt tbody td {
  padding-top: 0.5em;
  padding-bottom: 0.5em;
}
#receipt tfoot tr:first-child {
  border-top: 1px solid black !important;
}
#transaction .row div {
  display: inline-block;
}
#transaction #declined,
#transaction #declined * {
  text-align: center;
}
#transaction #declined p {
  font-size: 1.5rem;
  font-weight: bolder;
  margin: 0 0 0.25em;
}
#receipt {
  width: 100%;
}
#receipt *,
#transaction *,
#order *,
.thankyou {
  font-family: monospace, monospace !important;
  font-size: 13px !important;
}
#order {
  margin-top: 8px;
}
#order td {
  text-align: right;
}
@page {
  margin: 0;
}
</style>
```

## File: src/features/printing/order/shared-section.vue
```vue
<script setup lang="ts">
import { useCurrentOrderStore } from '../state';
import { useI18n } from 'vue-i18n';
import KnetSection from './knet-section.vue';
import CashierSection from './cashier-section.vue';
import { formatPrice } from '../../../../../../libs/utils';
const { t } = useI18n();
const { state } = useCurrentOrderStore();
</script>
<template>
  <table class="receipt-table">
    <tr>
      <th scope="col">{{ t('transaction_status') }}</th>
      <td>
        {{ state.order?.payments?.length > 0 ? t('approved') : t('declined') }}
      </td>
    </tr>
    <tr>
      <th scope="col" style="width: 50%">{{ t('transaction_id') }}</th>
      <td>{{ state.order?.unique_code }}</td>
    </tr>
    <cashier-section />
    <template v-if="state.order?.payments.length > 1">
      <tr>
        <td colspan="2">
          <hr />
        </td>
      </tr>
      <template v-for="payment in state?.order?.payments" :key="payment.id">
        <tr v-if="payment.payment_method_id">
          <th scope="col">{{ t('payment_method') }}</th>
          <td>{{ payment.readable_payment_method }}</td>
        </tr>
        <tr v-if="payment.auth_id">
          <th scope="col">{{ state.computed.authorization.label }}</th>
          <td>{{ payment.auth_id }}</td>
        </tr>
        <tr v-if="payment.amount">
          <th scope="col">Amount</th>
          <td>{{ formatPrice(payment.amount) }}</td>
        </tr>
        <tr>
          <td colspan="2">
            <hr />
          </td>
        </tr>
      </template>
    </template>
    <template v-else-if="state.order?.payments.length === 1">
      <tr>
        <th scope="col">{{ t('payment_method') }}</th>
        <td>{{ state.order?.payments[0].readable_payment_method }}</td>
      </tr>
      <tr v-if="state.computed.authorization.value">
        <th scope="col">{{ state.computed.authorization.label }}</th>
        <td>{{ state.computed.authorization.value }}</td>
      </tr>
    </template>
    <knet-section v-if="state.knetResponse" />
    <tr>
      <th scope="col">{{ t('terminal_id') }}</th>
      <td>{{ state.terminal_id.split('-')[0] }}</td>
    </tr>
    <tr v-if="state.order?.created_at">
      <th scope="col">{{ t('time') }}</th>
      <td>{{ state.order?.created_at }}</td>
    </tr>
    <tr>
      <td colspan="2">
        <barcode
          :value="state.order?.unique_code"
          format="CODE128"
          style="display: block; margin-top: 1em; margin-inline: auto"
        />
      </td>
    </tr>
  </table>
</template>
⋮----
<th scope="col">{{ t('transaction_status') }}</th>
⋮----
{{ state.order?.payments?.length > 0 ? t('approved') : t('declined') }}
⋮----
<th scope="col" style="width: 50%">{{ t('transaction_id') }}</th>
<td>{{ state.order?.unique_code }}</td>
⋮----
<template v-if="state.order?.payments.length > 1">
      <tr>
        <td colspan="2">
          <hr />
        </td>
      </tr>
      <template v-for="payment in state?.order?.payments" :key="payment.id">
        <tr v-if="payment.payment_method_id">
          <th scope="col">{{ t('payment_method') }}</th>
          <td>{{ payment.readable_payment_method }}</td>
        </tr>
        <tr v-if="payment.auth_id">
          <th scope="col">{{ state.computed.authorization.label }}</th>
          <td>{{ payment.auth_id }}</td>
        </tr>
        <tr v-if="payment.amount">
          <th scope="col">Amount</th>
          <td>{{ formatPrice(payment.amount) }}</td>
        </tr>
        <tr>
          <td colspan="2">
            <hr />
          </td>
        </tr>
      </template>
    </template>
⋮----
<template v-for="payment in state?.order?.payments" :key="payment.id">
        <tr v-if="payment.payment_method_id">
          <th scope="col">{{ t('payment_method') }}</th>
          <td>{{ payment.readable_payment_method }}</td>
        </tr>
        <tr v-if="payment.auth_id">
          <th scope="col">{{ state.computed.authorization.label }}</th>
          <td>{{ payment.auth_id }}</td>
        </tr>
        <tr v-if="payment.amount">
          <th scope="col">Amount</th>
          <td>{{ formatPrice(payment.amount) }}</td>
        </tr>
        <tr>
          <td colspan="2">
            <hr />
          </td>
        </tr>
      </template>
⋮----
<th scope="col">{{ t('payment_method') }}</th>
<td>{{ payment.readable_payment_method }}</td>
⋮----
<th scope="col">{{ state.computed.authorization.label }}</th>
<td>{{ payment.auth_id }}</td>
⋮----
<td>{{ formatPrice(payment.amount) }}</td>
⋮----
<template v-else-if="state.order?.payments.length === 1">
      <tr>
        <th scope="col">{{ t('payment_method') }}</th>
        <td>{{ state.order?.payments[0].readable_payment_method }}</td>
      </tr>
      <tr v-if="state.computed.authorization.value">
        <th scope="col">{{ state.computed.authorization.label }}</th>
        <td>{{ state.computed.authorization.value }}</td>
      </tr>
    </template>
⋮----
<th scope="col">{{ t('payment_method') }}</th>
<td>{{ state.order?.payments[0].readable_payment_method }}</td>
⋮----
<th scope="col">{{ state.computed.authorization.label }}</th>
<td>{{ state.computed.authorization.value }}</td>
⋮----
<th scope="col">{{ t('terminal_id') }}</th>
<td>{{ state.terminal_id.split('-')[0] }}</td>
⋮----
<th scope="col">{{ t('time') }}</th>
<td>{{ state.order?.created_at }}</td>
⋮----
<style>
.receipt-table {
  font-size: 13px;
  width: 100%;
}
.receipt-table td {
  text-align: right;
}
.receipt-table th {
  text-align: left;
}
</style>
```

## File: src/features/printing/receipts/decline-receipt.vue
```vue
<script lang="ts" setup>
import { declineReceiptRef } from '../printing-feature';
import BaseReceipt from '../base-receipt.vue';
import SharedSection from '../order/shared-section.vue';
</script>
<template>
  <div ref="declineReceiptRef">
    <base-receipt>
      <template #center>
        <div
          id="declined"
          style="
            font-size: 1.5rem;
            font-weight: bolder;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
          "
        >
          <p>DECLINED</p>
          <v-icon id="decline-icon" icon="mdi-close" size="3x" />
        </div>
      </template>
      <template #shared-section>
        <shared-section />
      </template>
    </base-receipt>
  </div>
</template>
⋮----
<template #center>
        <div
          id="declined"
          style="
            font-size: 1.5rem;
            font-weight: bolder;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
          "
        >
          <p>DECLINED</p>
          <v-icon id="decline-icon" icon="mdi-close" size="3x" />
        </div>
      </template>
<template #shared-section>
        <shared-section />
      </template>
⋮----
<style scoped></style>
```

## File: src/features/printing/receipts/reconciliation-receipt.vue
```vue
<script setup lang="ts">
import { reactive, ref } from 'vue';
import { useVueToPrint } from 'vue-to-print';
import { publish, subscribe } from '@enegix/events';
import { auth } from '../../../modules/auth';
import {
  PRINT_RECONCILIATION_RECEIPT,
  RECONCILIATION_RECEIPT_PRINTED,
} from '../events';
import { useSettings } from '../../../modules/settings/store';
const componentRef = ref();
const state = reactive({
  cashier_id: auth().state.auth.value?.username ?? '0000',
  cashierName: auth().state.auth.value?.name ?? 'Cashier',
  terminal_id: localStorage.getItem('tid') ?? '0000',
  warehouseName: auth().state.auth.value?.warehouse ?? 'Trolley',
  warehouse_id: auth().state.auth.value?.warehouse_id ?? '0000',
  knet_out: auth().state.knet_out,
  cash_out: auth().state.cash_out,
});
const handleAfterPrint = () => {
  publish(RECONCILIATION_RECEIPT_PRINTED);
};
const { handlePrint } = useVueToPrint({
  content: () => componentRef.value,
  documentTitle: 'trolley-reconciliation-receipt-' + Date.now().toString(),
  removeAfterPrint: true,
  onAfterPrint: handleAfterPrint,
});
subscribe(PRINT_RECONCILIATION_RECEIPT, handlePrint);
</script>
<template>
  <div ref="componentRef" style="width: 80mm; margin: auto">
    <table class="mb-2" id="receipt">
      <thead>
        <tr>
          <th scope="row" colspan="2" class="text-center">
            <img
              :src="useSettings()?.settings?.receipt_logo"
              style="width: 80px"
            />
            <p class="text-center mb-1">Reconciliation Receipt</p>
          </th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>Store ID:</th>
          <td>{{ state.warehouse_id }}</td>
        </tr>
        <tr>
          <th>Store Name:</th>
          <td>{{ state.warehouseName }}</td>
        </tr>
        <tr>
          <th>Cashier ID:</th>
          <td>{{ state.cashier_id }}</td>
        </tr>
        <tr>
          <th>Cashier Name:</th>
          <td>{{ state.cashierName }}</td>
        </tr>
        <tr>
          <th>Terminal ID:</th>
          <td>{{ state.terminal_id }}</td>
        </tr>
        <tr>
          <th>Date and Time:</th>
          <td>{{ new Date().toLocaleString() }}</td>
        </tr>
        <tr>
          <th>Cash Out:</th>
          <td>{{ state.cash_out }}</td>
        </tr>
        <tr>
          <th>KNet Out:</th>
          <td>{{ state.knet_out }}</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>
⋮----
<td>{{ state.warehouse_id }}</td>
⋮----
<td>{{ state.warehouseName }}</td>
⋮----
<td>{{ state.cashier_id }}</td>
⋮----
<td>{{ state.cashierName }}</td>
⋮----
<td>{{ state.terminal_id }}</td>
⋮----
<td>{{ new Date().toLocaleString() }}</td>
⋮----
<td>{{ state.cash_out }}</td>
⋮----
<td>{{ state.knet_out }}</td>
⋮----
<style>
.ml-auto {
  margin-left: auto;
}
.mt-2 {
  margin-top: 2em;
}
.mb-1 {
  margin-bottom: 1em;
}
.mb-2 {
  margin-bottom: 2em;
}
.float-right {
  float: right;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.font-weight-bolder {
  font-weight: bolder;
}
.nowrap {
  white-space: nowrap;
}
table {
  border-collapse: collapse;
}
th {
  text-align: left;
}
#receipt th,
#receipt td {
  padding: 5px;
}
@page {
  margin: 0;
}
</style>
```

## File: src/features/printing/receipts/refund-receipt.vue
```vue
<script lang="ts" setup>
import { PAYMENT_METHODS } from '@trolley/types';
import { useCurrentOrderStore } from '../state';
import { hasPayment } from '../helpers';
import { refundReceiptRef } from '../printing-feature';
import CashSection from '../order/cash-section.vue';
import BaseReceipt from '../base-receipt.vue';
const { state } = useCurrentOrderStore();
</script>
<template>
  <div ref="refundReceiptRef">
    <base-receipt>
      <template #payment-section>
        <cash-section
          type="refund"
          v-if="
            hasPayment(state.order?.payments ?? [], PAYMENT_METHODS.CASH) &&
            state?.order?.payments.length === 1
          "
        />
      </template>
    </base-receipt>
  </div>
</template>
⋮----
<template #payment-section>
        <cash-section
          type="refund"
          v-if="
            hasPayment(state.order?.payments ?? [], PAYMENT_METHODS.CASH) &&
            state?.order?.payments.length === 1
          "
        />
      </template>
```

## File: src/features/printing/receipts/sale-receipt.vue
```vue
<script lang="ts" setup>
import { useCurrentOrderStore } from '../state';
import { PAYMENT_METHODS } from '@trolley/types';
import { hasPayment } from '../helpers';
import BaseReceipt from '../base-receipt.vue';
import CashSection from '../order/cash-section.vue';
import { orderReceiptRef } from '../printing-feature';
import { useCustomer } from '../../../store/customer/state';
import { computed } from 'vue';
import { useSettings } from '../../../modules/settings/store';
const { state } = useCurrentOrderStore();
const customer = useCustomer();
const customer_name = computed(() => {
  const name =
    customer?.receiptCustomer?.name?.trim() || state?.order?.customer_name;
  return name === '_' ? '' : name;
});
</script>
<template>
  <div ref="orderReceiptRef">
    <base-receipt>
      <template #payment-section>
        <cash-section
          type="purchase"
          v-if="
            hasPayment(state.order?.payments ?? [], PAYMENT_METHODS.CASH) &&
            state?.order?.payments.length === 1
          "
        />
      </template>
      <template #footer>
        <p class="text-center font-weight-medium mt-4 mb-4">
          Thank You
          {{ customer_name }}
          for Shopping at {{ useSettings()?.settings?.brand_name }}
        </p>
        <p class="text-center text-caption text--secondary mt-2 mb-2">
          Exchange & Refund in 14 Days, T&C applied<br />
          إستبدال السلع وإعادتها خلال 14 يوم ,تطبق الشروط والأحكام
        </p>
      </template>
    </base-receipt>
  </div>
</template>
⋮----
<template #payment-section>
        <cash-section
          type="purchase"
          v-if="
            hasPayment(state.order?.payments ?? [], PAYMENT_METHODS.CASH) &&
            state?.order?.payments.length === 1
          "
        />
      </template>
<template #footer>
        <p class="text-center font-weight-medium mt-4 mb-4">
          Thank You
          {{ customer_name }}
          for Shopping at {{ useSettings()?.settings?.brand_name }}
        </p>
        <p class="text-center text-caption text--secondary mt-2 mb-2">
          Exchange & Refund in 14 Days, T&C applied<br />
          إستبدال السلع وإعادتها خلال 14 يوم ,تطبق الشروط والأحكام
        </p>
      </template>
⋮----
{{ customer_name }}
for Shopping at {{ useSettings()?.settings?.brand_name }}
```

## File: src/features/printing/base-receipt.vue
```vue
<script lang="ts" setup>
import { computed } from 'vue';
import { useCurrentOrderStore } from './state';
import SharedSection from './order/shared-section.vue';
import { isTransactionRefunded } from '../../store/transaction';
import { formatPrice } from '../../../../../libs/utils';
import { useSettings } from '../../modules/settings/store';
const { state } = useCurrentOrderStore();
const isRefundReceipt = computed(
  () => state?.order && isTransactionRefunded(state.order),
);
</script>
<template>
  <div id="base-receipt" style="width: 80mm; margin: auto">
    <table id="receipt" class="mb-2" style="font-size: 13px; width: 80mm">
      <thead style="display: table-row-group">
        <tr>
          <th class="text-center" colspan="4">
            <img
              :src="useSettings()?.settings?.receipt_logo"
              style="width: 80px"
            />
            <div
              style="
                font-family: Gadugi, serif !important;
                margin-top: 0.15rem;
                text-transform: capitalize;
              "
            >
              {{ state.branch?.name }}
            </div>
          </th>
        </tr>
        <tr>
          <th
            colspan="4"
            class="text-center"
            style="font-size: 16px; font-weight: bold"
          >
            <slot name="title">
              {{ isRefundReceipt ? 'Refund Receipt' : 'Sale Receipt' }}
            </slot>
          </th>
        </tr>
        <tr>
          <th class="w-25" style="text-align: left; padding-left: 0.5em">
            Item
          </th>
          <th class="w-25" style="text-align: center">Quantity</th>
          <th class="w-25" style="text-align: right">Unit Price</th>
          <th class="w-25" style="text-align: right">Total</th>
        </tr>
      </thead>
      <tbody>
        <template v-for="(item, index) in state.order?.items" :key="index">
          <tr>
            <td colspan="4" style="text-align: left; padding-left: 0.5em">
              {{ item.name }} / {{ item.name_ar }}
            </td>
          </tr>
          <tr>
            <td class="w-25"></td>
            <td class="w-25" style="text-align: center">
              {{ item.quantity }}
              <span v-if="item.is_weighted"> kg </span>
            </td>
            <td class="w-25" style="text-align: right">
              {{ formatPrice(item.price) }}
            </td>
            <td class="w-25" style="text-align: right">
              {{ item.getFormattedPrice?.() }}
            </td>
          </tr>
        </template>
      </tbody>
      <tfoot id="table-footer" style="display: table-row-group">
        <tr>
          <td colspan="3" class="text-right font-weight-bolder">
            NUMBER OF ITEMS
          </td>
          <td class="text-right font-weight-bolder">
            {{ state.computed.quantity }}
          </td>
        </tr>
        <tr>
          <td colspan="3" class="text-right font-weight-bolder">
            {{ isRefundReceipt ? 'REFUND SUBTOTAL' : 'SUBTOTAL' }}
          </td>
          <td class="text-right font-weight-bolder">
            {{ formatPrice(state.order?.sub_total) }}
          </td>
        </tr>
        <tr v-if="state.order?.redeem_amount_points">
          <td colspan="3" class="text-right font-weight-bolder">
            {{ isRefundReceipt ? 'REFUND Redeemed Points' : 'Redeemed Points' }}
          </td>
          <td class="text-right font-weight-bolder">
            {{ state.order.redeem_amount_points }}
          </td>
        </tr>
        <tr v-if="state.order?.earned_points">
          <td colspan="3" class="text-right font-weight-bolder">
            Earned Points
          </td>
          <td class="text-right font-weight-bolder">
            {{ state.order?.earned_points }}
          </td>
        </tr>
        <tr v-if="state.order?.redeemed_amount">
          <td colspan="3" class="text-right font-weight-bolder">
            {{ isRefundReceipt ? 'REFUND Redeemed Amount' : 'Redeemed Amount' }}
          </td>
          <td class="text-right font-weight-bolder">
            -{{ formatPrice(state.order.redeemed_amount) }}
          </td>
        </tr>
        <tr v-if="state.order?.discount_value">
          <td colspan="3" class="text-right font-weight-bolder">Discount</td>
          <td class="text-right font-weight-bolder">
            -{{ formatPrice(state.order.discount_value) }}
          </td>
        </tr>
        <tr>
          <td colspan="3" class="text-right font-weight-bolder">
            {{ isRefundReceipt ? 'REFUND TOTAL' : 'TOTAL' }}
          </td>
          <td class="text-right font-weight-bolder">
            {{ formatPrice(state.order?.amount ?? 0) }}
          </td>
        </tr>
        <tr
          v-if="
            state.computed.cash > 0 &&
            (isRefundReceipt || !state.computed.isSplit)
          "
        >
          <td colspan="3" class="text-right font-weight-bolder">
            {{ isRefundReceipt ? 'REFUND CASH' : 'CASH' }}
          </td>
          <td class="text-right font-weight-bolder">
            {{ formatPrice(state.computed.cash) }}
          </td>
        </tr>
        <tr v-if="state.computed.change > 0">
          <td colspan="3" class="text-right font-weight-bolder">
            {{ isRefundReceipt ? 'REFUND CHANGE' : 'CHANGE' }}
          </td>
          <td class="text-right font-weight-bolder">
            {{ formatPrice(state.computed.change) }}
          </td>
        </tr>
      </tfoot>
    </table>
    <slot name="center" />
    <shared-section />
    <slot name="footer" />
    <hr style="margin-top: 1.5em; margin-bottom: 5px" />
  </div>
</template>
⋮----
{{ state.branch?.name }}
⋮----
{{ isRefundReceipt ? 'Refund Receipt' : 'Sale Receipt' }}
⋮----
<template v-for="(item, index) in state.order?.items" :key="index">
          <tr>
            <td colspan="4" style="text-align: left; padding-left: 0.5em">
              {{ item.name }} / {{ item.name_ar }}
            </td>
          </tr>
          <tr>
            <td class="w-25"></td>
            <td class="w-25" style="text-align: center">
              {{ item.quantity }}
              <span v-if="item.is_weighted"> kg </span>
            </td>
            <td class="w-25" style="text-align: right">
              {{ formatPrice(item.price) }}
            </td>
            <td class="w-25" style="text-align: right">
              {{ item.getFormattedPrice?.() }}
            </td>
          </tr>
        </template>
⋮----
{{ item.name }} / {{ item.name_ar }}
⋮----
{{ item.quantity }}
⋮----
{{ formatPrice(item.price) }}
⋮----
{{ item.getFormattedPrice?.() }}
⋮----
{{ state.computed.quantity }}
⋮----
{{ isRefundReceipt ? 'REFUND SUBTOTAL' : 'SUBTOTAL' }}
⋮----
{{ formatPrice(state.order?.sub_total) }}
⋮----
{{ isRefundReceipt ? 'REFUND Redeemed Points' : 'Redeemed Points' }}
⋮----
{{ state.order.redeem_amount_points }}
⋮----
{{ state.order?.earned_points }}
⋮----
{{ isRefundReceipt ? 'REFUND Redeemed Amount' : 'Redeemed Amount' }}
⋮----
-{{ formatPrice(state.order.redeemed_amount) }}
⋮----
-{{ formatPrice(state.order.discount_value) }}
⋮----
{{ isRefundReceipt ? 'REFUND TOTAL' : 'TOTAL' }}
⋮----
{{ formatPrice(state.order?.amount ?? 0) }}
⋮----
{{ isRefundReceipt ? 'REFUND CASH' : 'CASH' }}
⋮----
{{ formatPrice(state.computed.cash) }}
⋮----
{{ isRefundReceipt ? 'REFUND CHANGE' : 'CHANGE' }}
⋮----
{{ formatPrice(state.computed.change) }}
⋮----
<style>
.header-icon {
  font-size: 0.7rem;
  margin: 0 0.2em;
  vertical-align: middle;
}
#base-receipt * {
  font-family: monospace, monospace !important;
  line-height: 1.3;
}
#close-icon {
  font-size: 0.8rem;
  margin: 0 0.2em;
}
#receipt thead tr:last-child {
  border-bottom: 1px solid black !important;
}
#receipt tbody td {
  padding-top: 0.5em;
  margin-bottom: 0.5em;
}
#receipt tfoot tr:first-child {
  border-top: 1px solid black !important;
  margin-top: 1.5em;
}
#transaction .row div {
  display: inline-block;
}
#transaction #declined,
#transaction #declined * {
  text-align: center;
}
#transaction #declined p {
  font-size: 1.5rem;
  font-weight: bolder;
  margin: 0 0 0.25em;
}
#receipt {
  width: 80mm;
}
#order td {
  text-align: right;
}
@page {
  margin: 0;
}
#table-footer * {
  line-height: 0.8;
}
#receipt .w-25 {
  width: 25% !important;
}
</style>
```

## File: src/features/printing/events.ts
```typescript
import { Topic } from '@enegix/events';
import type { KnetResponse } from '@trolley/knet';
import type { OrderData } from '@trolley/types';
⋮----
type PrintingTopic = {
  COMMAND_PRINT_ORDER: {
    order: OrderData;
    knetResponse?: KnetResponse;
    type: 'purchase' | 'refund';
  };
};
```

## File: src/features/printing/helpers.ts
```typescript
import { PAYMENT_METHODS } from '@trolley/types';
import { isCashPaymentMethod } from '@trolley/knet';
import { CompletedTransaction } from '@trolley/transactions';
export enum PrintableOrder {
  PURCHASE,
  REFUND,
}
export const isOrderRefund = (order: CompletedTransaction)
export const sumPaymentsByMethod = (
  payments: {
    payment_method_id: number;
    amount: number;
    extra?: string;
  }[],
  paymentMethodId: number,
) =>
export const calcCash = (
  payments: {
    payment_method_id: number;
    amount: number;
    extra?: string;
  }[],
) =>
export const calcCashChange = (
  payments: {
    payment_method_id: number;
    amount: number;
    extra?: string;
  }[],
  total: number,
) =>
export const hasPayment = (
  payments: { payment_method_id: number }[],
  paymentMethodId: number,
) =>
```

## File: src/features/printing/printing-feature.ts
```typescript
import { type Ref, ref, watch } from 'vue';
import { publish, subscribe } from '@enegix/events';
import { RECEIPT_PRINTED } from './events';
import { useVueToPrint } from 'vue-to-print';
import { useCurrentOrderStore } from './state';
import { CompletedTransaction, isTransactionPaid } from '@trolley/transactions';
import { wait } from 'nx-cloud/lib/utilities/waiter';
import { dialogTopic } from '../../components/dialogs/events';
import { EMPLOYEE_REQUESTS } from '../usecases/employee/events';
import { isOrderRefund } from './helpers';
import { openCashDrawer } from '../openCashDrawer';
⋮----
export const printingFeatureSubscribers = () =>
export const handlePrint = (templateRef: Ref)
const handleAfterPrint = () =>
```

## File: src/features/printing/state.ts
```typescript
import { defineStore } from 'pinia';
import type { KnetResponse } from '@trolley/knet';
import { ref, watch } from 'vue';
import { auth } from '../../modules/auth';
import { calcCash, hasPayment, sumPaymentsByMethod } from './helpers';
import { type OrderData, PAYMENT_METHODS } from '@trolley/types';
import { useSettings } from '../../modules/settings/store';
type ComputedValues = {
  cash: number;
  change: number;
  isCash: boolean;
  isKnetCard: boolean;
  isSplit: boolean;
  quantity: number;
  authorization: {
    label: string;
    value: string;
  };
};
type OrderReceiptProps = {
  branch: { name: string | undefined } | null;
  order:
    | (OrderData & {
        cashier_id: string;
        cashier_name: string;
      })
    | null;
  knetResponse: KnetResponse | null;
  computed: ComputedValues;
  terminal_id: string;
};
⋮----
const updateComputedValues = () =>
⋮----
// TODO: this will introduce a bug,
//  if we decided to allow talabat and deliveroo in split payments
⋮----
// @ts-expect-error
⋮----
const resetComputedValues = () =>
⋮----
function $reset()
```

## File: src/features/printing/types.ts
```typescript
export interface ReceiptTemplateProps {
  branch: string;
  items: { quantity: number; name: string; name_ar: string; price: number }[];
  customer: {
    name: string;
    redeem_amount: number;
    redeem_points: number;
    loyalty: { pointsBalance: number; pointsValue: number };
  };
  subtotal: number;
  total: number;
  transaction: {
    success: boolean;
    unique_code: string;
    id: string;
    cardType: string;
    cardNumber: string;
    time: string;
  };
}
```

## File: src/features/reinstall/reinstall-auth-dialog.vue
```vue
<script setup lang="ts">
import { ref } from 'vue';
import { publish, subscribe } from '@enegix/events';
import BaseDialog from '../../components/dialogs/base-dialog.vue';
import ProcessImage from './update.png';
import { trolleyClient } from '@trolley/api-sdk';
const showAuthDialog = ref(false);
const employeeId = ref('');
const password = ref('');
const loading = ref(false);
const errorMsg = ref<string | null>(null);
const formRef = ref();
const formIsValid = ref(false);
const rules = {
  employeeId: [(v: string) => /^\d{4}$/.test(v) || 'Must be exactly 4 digits'],
  password: [(v: string) => !!v || 'Password is required'],
};
subscribe('SHOW_REINSTALL_AUTH_DIALOG', () => {
  showAuthDialog.value = true;
});
const validateCredentials = async () => {
  const isValid = await formRef.value?.validate();
  if (!isValid) return;
  loading.value = true;
  errorMsg.value = null;
  try {
    await trolleyClient.default.postApiPosReinstallValidatePassword({
      formData: {
        employee_id: Number(employeeId.value),
        password: Number(password.value),
      },
    });
    showAuthDialog.value = false;
    publish('SHOW_REINSTALL_PROCESS_DIALOG');
  } catch (err: any) {
    errorMsg.value =
      err.response?.data?.message || err.message || 'Network error.';
  } finally {
    loading.value = false;
  }
};
</script>
<template>
  <base-dialog
    v-model="showAuthDialog"
    :img="ProcessImage"
    title="Reinstall POS – Employee Login"
    :text="`Please enter your employee ID and password to proceed with the re-installation process.`"
    :width="600"
    :on-close="
      () => {
        showAuthDialog = false;
        errorMsg = null;
        employeeId = '';
        password = '';
      }
    "
  >
    <v-form ref="formRef" v-model="formIsValid">
      <div class="p-4">
        <v-text-field
          v-model="employeeId"
          label="Employee ID (4 digits)"
          outlined
          dense
          maxlength="4"
          class="mb-4"
          :rules="rules.employeeId"
          autocomplete="userEmployee"
        />
        <v-text-field
          v-model="password"
          label="Password"
          type="password"
          outlined
          dense
          :rules="rules.password"
          autocomplete="new-password"
        />
        <div v-if="errorMsg" class="text-red-darken-2 text-sm mt-2">
          {{ errorMsg }}
        </div>
        <div class="mt-6 flex justify-start">
          <v-btn
            color="primary"
            block
            height="45"
            :loading="loading"
            :disabled="!formIsValid"
            @click="validateCredentials"
          >
            Submit
          </v-btn>
        </div>
      </div>
    </v-form>
  </base-dialog>
</template>
⋮----
{{ errorMsg }}
```

## File: src/features/reinstall/reinstall-process-dialog.vue
```vue
<script setup lang="ts">
import { computed, ref } from 'vue';
import BaseDialog from '../../components/dialogs/base-dialog.vue';
import { subscribe } from '@enegix/events';
import { toast } from 'vue3-toastify';
import { type ReinstallStep, useReinstall } from './use-reinstall';
const { steps, startReinstall } = useReinstall();
const showProcessDialog = ref(false);
const isRunning = ref(false);
const hadError = ref(false);
subscribe('SHOW_REINSTALL_PROCESS_DIALOG', () => {
  steps.value.forEach((s) => {
    s.status = 'pending';
    s.errorMessage = null;
  });
  hadError.value = false;
  showProcessDialog.value = true;
  isRunning.value = true;
  startReinstall()
    .catch(() => {
      hadError.value = true;
      toast.error('Reinstall failed. Please check the steps above.');
    })
    .finally(() => {
      isRunning.value = false;
    });
});
const retryReinstall = () => {
  hadError.value = false;
  steps.value.forEach((s) => {
    s.status = s.status === 'completed' ? 'completed' : 'pending';
    s.errorMessage = null;
  });
  isRunning.value = true;
  startReinstall()
    .catch(() => {
      hadError.value = true;
      toast.error('Reinstall failed. Please check the steps above.');
    })
    .finally(() => {
      isRunning.value = false;
    });
};
const closeDialog = () => {
  showProcessDialog.value = false;
};
const getStatusText = (status: ReinstallStep['status']) => {
  switch (status) {
    case 'pending':
      return 'Pending';
    case 'progress':
      return 'In progress…';
    case 'completed':
      return 'Completed';
    default:
      return '';
  }
};
const actions = computed(() => {
  const btns = [];
  if (hadError.value) {
    btns.push({
      text: 'Retry',
      handler: retryReinstall,
      disabled: isRunning.value,
      variant: 'elevated',
      color: 'primary',
    });
  }
  btns.push({
    text: 'Close',
    handler: closeDialog,
    disabled: isRunning.value,
    variant: 'outlined',
    color: 'weakTextColor',
  });
  return btns;
});
</script>
<template>
  <BaseDialog
    v-model="showProcessDialog"
    title="Reinstall POS – Step-by-Step"
    persistent
    :closeable="!isRunning"
    width="600"
  >
    <div class="update-progress">
      <div v-if="hadError" class="error-message">
        Reinstall failed. Please review the steps below.
      </div>
      <template v-else>
        <div v-for="step in steps" :key="step.title" class="step">
          <div class="step-icon">
            <template v-if="step.status === 'completed'">✓</template>
            <v-progress-circular
              v-else-if="step.status === 'in-progress'"
              indeterminate
              size="20"
              width="2"
            />
            <template v-else>◯</template>
          </div>
          <div class="step-title">{{ step.title }}</div>
          <div class="step-status">{{ getStatusText(step.status) }}</div>
        </div>
      </template>
    </div>
    <div class="button-container">
      <v-btn
        v-for="(action, index) in actions"
        :key="index"
        @click="action.handler"
        :disabled="action.disabled"
        class="action-button text-capitalize"
        :color="action.color"
        :variant="action.variant"
        height="auto"
      >
        {{ action.text }}
      </v-btn>
    </div>
  </BaseDialog>
</template>
⋮----
<template v-else>
        <div v-for="step in steps" :key="step.title" class="step">
          <div class="step-icon">
            <template v-if="step.status === 'completed'">✓</template>
            <v-progress-circular
              v-else-if="step.status === 'in-progress'"
              indeterminate
              size="20"
              width="2"
            />
            <template v-else>◯</template>
          </div>
          <div class="step-title">{{ step.title }}</div>
          <div class="step-status">{{ getStatusText(step.status) }}</div>
        </div>
      </template>
⋮----
<template v-if="step.status === 'completed'">✓</template>
⋮----
<template v-else>◯</template>
⋮----
<div class="step-title">{{ step.title }}</div>
<div class="step-status">{{ getStatusText(step.status) }}</div>
⋮----
{{ action.text }}
⋮----
<style scoped>
.update-progress {
  margin: 1rem 0;
}
.error-message {
  color: #ff4444;
  padding: 1rem;
  background: #ffeeee;
  border-radius: 4px;
  margin-bottom: 1rem;
  font-weight: 500;
}
.step {
  display: flex;
  align-items: center;
  padding: 0.5rem 0;
  border-bottom: 1px solid #eee;
}
.step-icon {
  width: 30px;
  margin-right: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
}
.step-title {
  flex-grow: 1;
  color: rgba(0, 0, 0, 0.87);
  font-weight: 500;
}
.step-status {
  color: rgba(0, 0, 0, 0.54);
  margin-left: 1rem;
  font-size: 0.9rem;
}
.button-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  max-width: 650px;
  gap: 10px;
  margin-top: 1rem;
}
.action-button {
  flex-grow: 1;
  flex-basis: calc(50% - 10px);
  padding: 10px;
}
</style>
```

## File: src/features/reinstall/use-reinstall.ts
```typescript
import { getCachedEntity, trolleyClient } from '@trolley/api-sdk';
import { toast } from 'vue3-toastify';
import { ref } from 'vue';
import { resolveAfterDelay } from '@trolley/utils';
import { checkBackendHealth } from '../app-mode/backend-status-topic';
import {
  clearCaches,
  unregisterServiceWorker,
} from '../../modules/settings/version-update';
import { TERMINAL_ID } from '../../env';
export enum ReinstallSteps {
  CHECK_BACKEND = 'Checking backend health',
  SYNC_TRANSACTIONS = 'Syncing pending transactions',
  CLEAR_CACHES = 'Clearing caches & assets',
  CLEAR_SW = 'Unregistering service workers',
  CLEAR_STORAGE = 'Clearing local storage & cookies',
  COMPLETE = 'Redirecting to clean install',
}
export interface ReinstallStep {
  title: ReinstallSteps;
  status: 'pending' | 'in-progress' | 'completed' | 'error';
  errorMessage?: string | null;
}
export function useReinstall()
⋮----
function updateStep(
    stepTitle: ReinstallSteps,
    status: ReinstallStep['status'],
    errorMessage: string | null = null,
)
async function areTransactionsEmpty(): Promise<boolean>
async function checkReinstallAvailability(): Promise<void>
async function stepCheckBackend(): Promise<void>
async function stepSyncTransactions(): Promise<void>
async function stepClearCaches(): Promise<void>
async function stepUnregisterSW(): Promise<void>
async function stepClearStorage(): Promise<void>
async function stepRedirect(): Promise<void>
async function startReinstall(): Promise<void>
```

## File: src/features/sync-check/state.ts
```typescript
import { useLocalStorage } from '@vueuse/core';
```

## File: src/features/sync-check/sync-check-dialog.vue
```vue
<script setup lang="ts">
import { ref, watch } from 'vue';
import BaseDialog from '../../components/dialogs/base-dialog.vue';
import { useHealthCheck } from './use-health-check';
import { publish } from '@enegix/events';
import { removeAllSyncHealthChecks } from '../../utils/sync';
import { isSyncCheckDialogClosed } from './state';
const dialogVisible = ref(false);
watch(
  isSyncCheckDialogClosed,
  (value) => {
    dialogVisible.value = !value;
  },
  {
    immediate: true,
  },
);
const { checks } = useHealthCheck();
const handleRemoveCache = () => {
  removeAllSyncHealthChecks();
  publish('clear-cache-voidReasons');
  publish('clear-cache-quickList');
  publish('clear-cache-settings');
  publish('clear-cache-items');
  publish('clear-cache-paymentMethods');
  publish('clear-cache-users');
  setTimeout(() => window.location.reload(), 1000);
};
const handleConfirm = () => {
  dialogVisible.value = false;
  isSyncCheckDialogClosed.value = true;
};
</script>
<template>
  <base-dialog
    persistent
    v-model="dialogVisible"
    header-text="POS Health Check"
  >
    <div class="info-container mt-6 px-4">
      <div v-for="check in checks" :key="check.label" class="check-item">
        <p>
          <strong>{{ check.label }}</strong>
        </p>
        <transition name="fade">
          <span v-if="check.status === 'loading'" class="status-icon loading">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 100 100"
              class="spinner"
            >
              <circle
                cx="50"
                cy="50"
                r="45"
                stroke="currentColor"
                stroke-width="10"
                fill="none"
                stroke-dasharray="283"
                stroke-dashoffset="75"
              />
            </svg>
          </span>
          <span v-else-if="check.status === 'ready'" class="status-icon ready">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
            >
              <path
                d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7 19.59 5.59 9 16.17z"
              />
            </svg>
          </span>
          <span v-else class="status-icon error">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="currentColor"
            >
              <path
                d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm-1-13h2v6h-2zm0 8h2v2h-2z"
              />
            </svg>
          </span>
        </transition>
      </div>
      <div class="buttons">
        <v-btn
          @click="handleRemoveCache"
          width="50%"
          color="second"
          variant="tonal"
        >
          Re-sync
        </v-btn>
        <v-btn
          :disabled="!checks.every((check) => check.status === 'ready')"
          @click="handleConfirm"
          width="50%"
          color="primary"
        >
          Confirm
        </v-btn>
      </div>
    </div>
  </base-dialog>
</template>
⋮----
<strong>{{ check.label }}</strong>
⋮----
<style scoped>
.buttons {
  display: flex;
  gap: 1rem;
  margin-top: 1rem;
}
.info-container {
  max-height: 60vh;
  width: 40vw;
  overflow-y: auto;
}
.check-item {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #eaeaea;
  padding-inline: 8px;
}
.status-icon {
  font-size: 1.5rem;
  margin-left: 1rem;
}
.status-icon.loading svg {
  width: 24px;
  height: 24px;
  color: #f39c12;
  animation: spin 1s linear infinite;
}
.status-icon.ready svg {
  width: 24px;
  height: 24px;
  color: #2ecc71;
}
.status-icon.error svg {
  width: 24px;
  height: 24px;
  color: #e74c3c;
}
@keyframes spin {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
</style>
```

## File: src/features/sync-check/use-health-check.ts
```typescript
import { onMounted, reactive, watch } from 'vue';
import { useBackendStatusCheck } from '../app-mode/check';
import { useSettingsCheck } from '../../modules/settings/health-check';
import { useItemsCheck } from '../items/check';
import { useUsersCheck } from '../users/check';
import { useQuickListCheck } from '../../modules/quick-list/health-check';
import { useVoidReasonsCheck } from '../void-reasons/check';
import { usePaymentMethodsCheck } from '../payment-methods/check';
export type HealthStatus = 'loading' | 'ready' | 'error';
interface CheckItem {
  label: string;
  status: HealthStatus;
  countable?: boolean;
  count?: number;
}
⋮----
export type CheckLabel = (typeof checks)[number]['label'];
const getCheck = (label: CheckLabel) =>
export const useHealthCheck = () =>
⋮----
const runCheck = async (
    checkFunction: () => Promise<any>,
    label: CheckLabel,
) =>
```

## File: src/features/tests/posthog.spec.ts
```typescript
import { describe, it, expect, vi, beforeEach } from 'vitest';
⋮----
import posthog from 'posthog-js';
⋮----
import { AUTH_EVENTS } from '../../modules/auth/events';
```

## File: src/features/usecases/employee/events.ts
```typescript
export enum EMPLOYEE_REQUESTS {
  VOID_SALE = 'VOID_SALE',
  STASH_SALE = 'STASH_SALE',
  PRINT_DECLINED_RECEIPT = 'PRINT_DECLINED_RECEIPT',
}
export enum CART_ACTIONS {
  SHOW_CART_COUPONS = 'SHOW_CART_COUPONS',
}
```

## File: src/features/usecases/payments/knet/automatic/knet-connection-indicator.vue
```vue
<script lang="ts" setup>
import { computed, ref } from 'vue';
import { KNET_CONNECTION_COMMANDS, KNET_CONNECTION_STATE, knetMachineTopic } from '@trolley/knet';
const connectionState = ref<KNET_CONNECTION_STATE>(
  KNET_CONNECTION_STATE.DISCONNECTED,
);
knetMachineTopic.subscribe('STATUS', (status) => {
  connectionState.value = status;
});
const connectionDetails = computed(() => {
  const state = connectionState.value;
  const details = {
    color: 'weakTextColor',
    icon: 'mdi-circle',
    animationClass: 'fade-in',
  };
  if (
    state === KNET_CONNECTION_STATE.CONNECTED ||
    state === KNET_CONNECTION_STATE.PONG
  ) {
    details.color = 'primary';
    details.icon = 'mdi-check-circle';
  } else if (state === KNET_CONNECTION_STATE.DISCONNECTED) {
    details.icon = 'mdi-alert-circle';
  } else if (state === KNET_CONNECTION_STATE.CONNECTING) {
    details.color = 'primary';
    details.icon = 'mdi-cached';
    details.animationClass = 'rotate';
  }
  return details;
});
const handleClick = () => {
  if (connectionState.value === KNET_CONNECTION_STATE.DISCONNECTED) {
    knetMachineTopic.publish('COMMANDS', KNET_CONNECTION_COMMANDS.RECONNECT);
  } else {
    knetMachineTopic.publish('COMMANDS', KNET_CONNECTION_COMMANDS.DISCONNECT);
  }
};
</script>
<template>
  <v-list-item
    class="d-flex flex-column justify-center align-center mt-4 transition"
    link
    @click="handleClick"
    disabled
    :style="{ opacity: 1 }"
  >
    <template #prepend>
      <v-icon
        :color="connectionDetails.color"
        :class="['ms-8', 'mdi', connectionDetails.animationClass]"
      >
        {{ connectionDetails.icon }}
      </v-icon>
    </template>
    <template #title>
      <p class="text-weakTextColor nav-items-title fade-in mt-1">KNET</p>
    </template>
  </v-list-item>
  <v-divider />
</template>
⋮----
<template #prepend>
      <v-icon
        :color="connectionDetails.color"
        :class="['ms-8', 'mdi', connectionDetails.animationClass]"
      >
        {{ connectionDetails.icon }}
      </v-icon>
    </template>
⋮----
{{ connectionDetails.icon }}
⋮----
<template #title>
      <p class="text-weakTextColor nav-items-title fade-in mt-1">KNET</p>
    </template>
⋮----
<style scoped>
.nav-items-title {
  font-size: 9px;
}
.fade-in {
  animation: fadeIn 1s ease-in-out;
}
.rotate {
  animation: rotate 1s linear infinite;
}
@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(-360deg);
  }
}
</style>
```

## File: src/features/usecases/scanner/events.ts
```typescript
import onScan from 'onscan.js';
import { Topic } from '@enegix/events';
import {
  CART_TAB,
  CHECKOUT_TAB,
  COUPON_TAB,
  globalStore,
  REFUND_PAGE,
} from '../../../store/global';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { trolleyClient } from '@trolley/api-sdk';
type ScannerTopic = {
  SCANNED_PRODUCT: string;
  SCANNED_RECEIPT: string;
  SCANNED_COUPON: string;
};
⋮----
export const scannerFeatureHandler = () =>
```

## File: src/features/users/check.ts
```typescript
import { ref } from 'vue';
import type { HealthStatus } from '../sync-check/use-health-check';
import { z } from 'zod';
import { getCachedEntity, trolleyClient } from '@trolley/api-sdk';
⋮----
export const useUsersCheck = async () =>
```

## File: src/features/void-reasons/cart-void-dialog.vue
```vue
<template>
  <BaseDialog
    v-model="dialogVisible"
    :title="t('void?')"
    :text="t('void_text')"
    :on-close="() => (dialogVisible = false)"
  >
    <div class="button-container">
      <v-btn
        v-for="(action, index) in actions"
        :key="index"
        @click="action.handler"
        class="action-button text-capitalize"
        color="weakTextColor"
        variant="outlined"
        height="auto"
        density="default"
        :loading="usePendingTransactionStore().isSubmitting"
        :disabled="usePendingTransactionStore().isSubmitting"
        >{{ action.text }}
      </v-btn>
    </div>
  </BaseDialog>
</template>
⋮----
>{{ action.text }}
⋮----
<script setup lang="ts">
import { computed, onBeforeMount, ref } from 'vue';
import { publish, subscribe } from '@enegix/events';
import BaseDialog from '../../components/dialogs/base-dialog.vue';
import { SHOW_VOID_DIALOG } from '../usecases/employee/events';
import { useVoidReasons } from './store';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { toast } from 'vue3-toastify';
import { TRANSACTION_EVENTS } from '@trolley/transactions';
import { useI18n } from 'vue-i18n';
const { t } = useI18n();
const dialogVisible = ref(false);
const actions = computed(() =>
  useVoidReasons().state.reasons.map((reason) => ({
    text: reason.name,
    handler: () => {
      usePendingTransactionStore()
        .voidTransaction(reason.id)
        .then(() => {
          publish(TRANSACTION_EVENTS.VOID, reason.id);
          toast.success('Transaction voided successfully');
          dialogVisible.value = false;
        });
    },
  })),
);
subscribe(SHOW_VOID_DIALOG, async () => {
  dialogVisible.value = true;
  await useVoidReasons().fetchVoidReasons();
});
onBeforeMount(async () => await useVoidReasons().fetchVoidReasons());
</script>
<style scoped>
.button-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  max-width: 650px;
  gap: 10px;
  margin-top: 1rem;
}
.action-button {
  flex-grow: 1;
  flex-basis: calc(50% - 10px);
  padding: 10px;
}
</style>
```

## File: src/features/void-reasons/check.ts
```typescript
import { z } from 'zod';
import type { HealthStatus } from '../sync-check/use-health-check';
import { ref } from 'vue';
import { useVoidReasons } from './store';
import { getCachedEntity } from '@trolley/api-sdk';
⋮----
export const useVoidReasonsCheck = async () =>
```

## File: src/features/void-reasons/store.ts
```typescript
import { defineStore } from 'pinia';
import { ref } from 'vue';
import type { IVoidReason } from '@trolley/types';
import { trolleyClient } from '@trolley/api-sdk';
⋮----
const fetchVoidReasons = async () =>
```

## File: src/features/after-auth-employee-features.ts
```typescript
import { scannerFeatureHandler } from './usecases/scanner/events';
import { printingFeatureSubscribers } from './printing/printing-feature';
import { startSessionTracker } from './session-trackers';
import { assignTrolleyClient, initKnetSocketService } from '@trolley/knet';
import { trolleyClient } from '@trolley/api-sdk';
⋮----
bootstrap(features: Record<string, boolean>)
```

## File: src/features/openCashDrawer.ts
```typescript
import axios from 'axios';
import { toast } from 'vue3-toastify';
export const openCashDrawer = async () =>
```

## File: src/features/openreplay.ts
```typescript
import Tracker from '@openreplay/tracker';
import trackerAssist from '@openreplay/tracker-assist';
import { useAuthStore } from '../modules/auth/store';
import { subscribe } from '@enegix/events';
import { type Auth } from '../modules/auth';
import { AUTH_EVENTS } from '../modules/auth/events';
⋮----
function createTracker()
function setMetaData(userId)
export function startOpenReplayTracker()
```

## File: src/features/posthog.ts
```typescript
import posthog from 'posthog-js';
import { useAuthStore } from '../modules/auth/store';
import { subscribe } from '@enegix/events';
import { AUTH_EVENTS } from '../modules/auth/events';
import { ENVIRONMENT, TERMINAL_ID } from '../env';
import type { Auth } from '../modules/auth';
⋮----
function getEnvVars()
export function identifyUser(auth: Auth)
export function startPostHogTracker()
export function resetInitialized()
```

## File: src/features/pre-auth-features.ts
```typescript
import {
  initAppMode,
  setupAppModeWatchers,
} from './app-mode/backend-status-topic';
import { startInterval, trolleyClient } from '@trolley/api-sdk';
import { versionUpdateFeature } from '../modules/settings/version-update';
⋮----
bootstrap()
```

## File: src/features/session-trackers.ts
```typescript
import { startOpenReplayTracker } from './openreplay';
import { startPostHogTracker } from './posthog';
export function startSessionTracker(features: {
  openreplay?: boolean;
  posthog?: boolean;
})
```

## File: src/layouts/clientView.vue
```vue
<template>
  <div class="fill-height" @dblclick="goFullscreen()">
    <v-btn
      v-if="!isFullscreen"
      @click="goFullscreen"
      color="primary"
      style="
        position: fixed;
        bottom: 50%;
        left: 0;
        z-index: 1000;
        border-radius: 0 8px 8px 0;
      "
    >
      <v-icon>mdi-fullscreen</v-icon>
    </v-btn>
    <v-sheet
      v-if="isCartEmpty"
      class="fill-screen d-flex align-center justify-center fill-height"
      elevation="0"
      tile
    >
      <transition name="fade" @after-leave="showVideo">
        <div v-if="showLogo" class="splash-screen">
          <AppLogo class="splash-logo" />
        </div>
      </transition>
      <video-screen :video="activeVideo" @ready="onVideoReady" />
    </v-sheet>
    <v-sheet v-else>
      <v-layout class="rounded rounded-md" style="overflow: hidden">
        <v-main style="min-height: 100dvh; width: calc(100dvw - 450px)">
          <router-view />
        </v-main>
        <aside class="panel-options">
          <div class="d-flex justify-space-between align-center panel-title">
            <p v-if="useLoyaltyStore().is_loyalty_enabled">
              <v-icon icon="mdi mdi-menu"></v-icon>
              {{ t('loyalty') }}
            </p>
            <div class="pos-logo">
              <AppLogo />
            </div>
          </div>
          <router-view name="aside" />
        </aside>
      </v-layout>
    </v-sheet>
    <dialog-manager />
  </div>
</template>
⋮----
{{ t('loyalty') }}
⋮----
<script setup>
import DialogManager from '../components/dialogs/dialog-manager.vue';
import AppLogo from '../components/appLogo.vue';
import { useClientScreen } from '../store/clientScreen';
import { computed, onMounted, ref } from 'vue';
import {
  usePendingTransactionStore,
  useRefundTransactionStore,
} from '@trolley/transactions/vue';
import { multiTabBroadcast } from '../features/multi-tab/multi-tab-broadcast';
import { useI18n } from 'vue-i18n';
import { goFullscreen } from '../utils/utils';
import VideoScreen from '../modules/advertisement/video-screen.vue';
import { useLoyaltyStore } from '../modules/loyalty/store/loyalty-store';
import { useSettings } from '../modules/settings/store';
import { whenever } from '@vueuse/core';
const isFullscreen = ref(false);
const settings = useSettings();
const isVideoVisible = ref(false);
const isVideoReady = ref(false);
const fallbackVideo = {
  id: '1',
  url: 'https://trolleyecom.s3.me-south-1.amazonaws.com/pos/trolley.mp4',
};
onMounted(() => {
  document.addEventListener('fullscreenchange', () => {
    isFullscreen.value = document.fullscreenElement !== null;
  });
  multiTabBroadcast.channel.value.addEventListener('message', (event) => {
    if (event.data === 'close-tab') {
      close();
      window.close();
    }
  });
});
const { t } = useI18n();
const activeVideo = computed(() => {
  return settings.settings?.video?.url
    ? settings.settings.video
    : fallbackVideo;
});
const showLogo = computed(() => !isVideoReady.value);
const activeTransaction = computed(() =>
  useRefundTransactionStore().itemsManager.totalItems > 0
    ? useRefundTransactionStore()
    : usePendingTransactionStore(),
);
let clientScreen = useClientScreen();
setInterval(() => {
  clientScreen.openLock = new Date().getTime();
}, 1000);
const showVideo = () => {
  isVideoVisible.value = true;
};
const onVideoReady = () => {
  isVideoVisible.value = true;
  isVideoReady.value = true;
};
const isCartEmpty = computed(
  () => activeTransaction.value.itemsManager.totalItems === 0,
);
whenever(isCartEmpty, showVideo);
</script>
<style scoped>
.wrapper {
  height: 100vh;
  display: flex;
  justify-content: center;
}
.fade-enter-active,
.fade-leave-active {
  transition: opacity 1s;
}
.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}
.splash-screen {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
  width: 100%;
}
.splash-logo {
  max-width: 300px;
  max-height: 300px;
  object-fit: contain;
}
.pos-logo {
  width: 100px;
  height: 100%;
}
</style>
```

## File: src/layouts/employeeView.vue
```vue
<template>
  <v-locale-provider>
    <v-layout class="rounded rounded-md" full-height style="overflow: hidden">
      <side-nav-vue />
      <v-main style="min-height: 100dvh; width: calc(100dvw - 600px)">
        <v-sheet class="bg-background mr-0 ml-0 content-area h-100 relative">
          <header-section :isClient="false" />
          <router-view />
        </v-sheet>
        <calculator />
        <logout-sheet />
      </v-main>
      <aside class="panel-options">
        <panel-title icon="mdi mdi-menu" title="items_catalog" />
        <router-view name="aside" />
      </aside>
      <div class="hidden">
        <sale-receipt />
        <decline-receipt />
        <refund-receipt />
        <reconciliation-receipt />
      </div>
    </v-layout>
    <dialog-manager />
  </v-locale-provider>
</template>
<script lang="ts" setup>
import SideNavVue from '../views/sideNav.vue';
import headerSection from '../components/mainScreen/header-section/headerSection.vue';
import DialogManager from '../components/dialogs/dialog-manager.vue';
import PanelTitle from '../components/aside/panelTitle.vue';
import Calculator from '../components/calculator.vue';
import LogoutSheet from '../components/bottomSheets/logoutSheet.vue';
import { onMounted } from 'vue';
import ReconciliationReceipt from '../features/printing/receipts/reconciliation-receipt.vue';
import afterAuthEmployeeFeatures from '../features/after-auth-employee-features';
import { multiTabBroadcast } from '../features/multi-tab/multi-tab-broadcast';
import { openClientPage } from '../utils/utils';
import SaleReceipt from '../features/printing/receipts/sale-receipt.vue';
import DeclineReceipt from '../features/printing/receipts/decline-receipt.vue';
import RefundReceipt from '../features/printing/receipts/refund-receipt.vue';
import { useSettings } from '../modules/settings/store';
onMounted(async () => {
  const settings = useSettings();
  if (!settings.settings) {
    await settings.fetchSettings();
  }
  afterAuthEmployeeFeatures.bootstrap(settings.settings?.features || {});
  openClientPage();
  addEventListener('beforeunload', () => {
    multiTabBroadcast.post('close-tab');
  });
});
</script>
<style scoped>
.hidden {
  display: none;
}
</style>
```

## File: src/layouts/emptyView.vue
```vue
<template>
  <v-locale-provider>
    <router-view />
  </v-locale-provider>
</template>
```

## File: src/modules/advertisement/banner-carousel.vue
```vue
<template>
  <v-carousel
    hide-delimiters
    cycle
    :show-arrows="false"
    v-model="currentSlide"
    :interval="currentInterval * 1000"
    height="auto"
  >
    <v-carousel-item
      rounded="lg"
      eager
      v-for="(item, index) in resolvedSlides"
      :key="index"
      cover
    >
      <img
        :src="item.url"
        class="panel rounded"
        alt="Advertisement"
      />
    </v-carousel-item>
  </v-carousel>
</template>
<script setup lang="ts">
import { computed, ref, watch } from 'vue';
import { useSettings } from '../settings/store';
interface BannerItem {
  url: string;
  duration?: number;
}
const props = defineProps<{
  items?: BannerItem[];
  defaultInterval?: number;
}>();
const DEFAULT_INTERVAL = props.defaultInterval ?? 5;
const currentSlide = ref(0);
const settingsStore = useSettings();
const resolvedSlides = computed(() => props.items ?? settingsStore.settings?.banners ?? []);
const currentInterval = ref(
  resolvedSlides.value[currentSlide.value]?.duration ?? DEFAULT_INTERVAL
);
watch(currentSlide, () => {
  currentInterval.value =
    resolvedSlides.value[currentSlide.value]?.duration ?? DEFAULT_INTERVAL;
});
</script>
<style scoped>
.panel {
  width: 100%;
  aspect-ratio: 16 / 9;
}
</style>
```

## File: src/modules/advertisement/video-screen.vue
```vue
<template>
  <div class="video-carousel">
    <transition-group v-if="videos.length > 1" name="fade" tag="div">
      <video
        v-for="(vid, idx) in videos"
        v-show="idx === currentIndex"
        :key="vid.id"
        ref="videoRef"
        :src="vid.url"
        autoplay
        class="video"
        muted
        playsinline
        @canplaythrough="onReady"
        @ended="handleVideoEnd"
      />
    </transition-group>
    <video
      v-else
      ref="videoRef"
      :src="videos[0].url"
      autoplay
      class="video"
      loop
      @canplaythrough="onReady"
      muted
      playsinline
    />
  </div>
</template>
<script lang="ts" setup>
import { computed, ref } from 'vue';
interface VideoItem {
  id: string;
  url: string;
}
const props = defineProps<{
  video: VideoItem | VideoItem[];
}>();
const emit = defineEmits(['ready']);
const onReady = () => {
  emit('ready');
};
const videos = computed(() =>
  Array.isArray(props.video) ? props.video : [props.video]
);
const videoRef = ref<HTMLVideoElement | null>(null);
const currentIndex = ref(0);
const handleVideoEnd = () => {
  if (videos.value.length > 1) {
    currentIndex.value = currentIndex.value < videos.value.length - 1
      ? currentIndex.value + 1
      : 0;
  }
};
</script>
<style scoped>
.video-carousel {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
  overflow: hidden;
  display: flex;
  align-items: stretch;
  justify-content: center;
}
.video {
  width: 100%;
  height: 100%;
  object-fit: cover;
  position: absolute;
  top: 0;
  left: 0;
}
.fade-enter-active,
.fade-leave-active {
  transition: opacity 1s ease;
}
.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}
</style>
```

## File: src/modules/auth/events.ts
```typescript

```

## File: src/modules/auth/index.ts
```typescript
import { useAuthStore } from './store';
import { storeToRefs } from 'pinia';
⋮----
export const auth = () => (
```

## File: src/modules/auth/store.ts
```typescript
import { defineStore } from 'pinia';
import { computed, ref, watch } from 'vue';
import type { Auth } from './types';
import { subscribe } from '@enegix/events';
import { AUTH_EVENTS } from './events';
import { formatPrice } from '@trolley/utils';
import { useLocalStorage, useStorage } from '@vueuse/core';
⋮----
const clearAuth = () =>
```

## File: src/modules/auth/types.ts
```typescript
export interface Auth {
  token: string;
  type: number;
  skip_payment: boolean;
  warehouse: string;
  warehouse_id: number;
  terminal_name?: string;
  name: string;
  cashier_id: number;
  username: string;
  sequence: string;
}
```

## File: src/modules/loyalty/assets/compare-arrows.vue
```vue
<template>
  <div class="text-primary">
    <svg
      fill="currentColor"
      height="auto"
      preserveAspectRatio="xMidYMid meet"
      viewBox="0 0 12.5 8.75"
      width="100%"
      xmlns="http://www.w3.org/2000/svg"
    >
      <path
        d="M5.631,8.75H1.25V10H5.631v1.875l2.494-2.5-2.494-2.5Zm3.737-.625V6.25H13.75V5H9.369V3.125l-2.494,2.5Z"
        transform="translate(-1.25 -3.125)"
      />
    </svg>
  </div>
</template>
```

## File: src/modules/loyalty/assets/crown.svg
```
<svg enable-background="new 0 0 32 32" height="512" viewBox="0 0 32 32" width="512" xmlns="http://www.w3.org/2000/svg"><g id="Layer_1"><g><g fill="#ffb743"><path d="m2.8373 20.9773c-.6083-3.954-1.2166-7.9079-1.8249-11.8619-.1349-.8765.8624-1.4743 1.5718-.9422 1.8952 1.4214 3.7903 2.8427 5.6855 4.2641.624.468 1.513.3157 1.9456-.3333l4.7333-7.1c.5002-.7503 1.6026-.7503 2.1028 0l4.7333 7.1c.4326.649 1.3216.8012 1.9456.3333 1.8952-1.4214 3.7903-2.8427 5.6855-4.2641.7094-.5321 1.7067.0657 1.5719.9422-.6083 3.954-1.2166 7.9079-1.8249 11.8619z"/><path d="m27.7902 27.5586h-23.5804c-.758 0-1.3725-.6145-1.3725-1.3725v-3.015h26.3255v3.015c-.0001.758-.6146 1.3725-1.3726 1.3725z"/></g></g></g></svg>
```

## File: src/modules/loyalty/assets/loyality-card-01.svg
```
<?xml version="1.0" encoding="UTF-8"?>
<svg data-name="Layer 2" id="Layer_2" version="1.1" viewBox="0 0 446 219" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      .cls-1 {
        fill: #fbb040;
      }

      .cls-1, .cls-2, .cls-3, .cls-4, .cls-5, .cls-6, .cls-7, .cls-8, .cls-9, .cls-10, .cls-11, .cls-12, .cls-13, .cls-14, .cls-15, .cls-16, .cls-17, .cls-18, .cls-19, .cls-20 {
        stroke-width: 0px;
      }

      .cls-2 {
        fill: #ecc19c;
      }

      .cls-3 {
        fill: #df4800;
      }

      .cls-21 {
        clip-path: url(#clippath);
      }

      .cls-4 {
        fill: none;
      }

      .cls-22 {
        opacity: 0;
      }

      .cls-5 {
        fill: #f4b400;
      }

      .cls-6 {
        fill: #feb400;
      }

      .cls-7 {
        fill: #fe6800;
      }

      .cls-8 {
        fill: url(#radial-gradient);
      }

      .cls-9 {
        fill: #a51e1b;
      }

      .cls-10 {
        fill: #fe9500;
      }

      .cls-11 {
        fill: #fe7e00;
      }

      .cls-23 {
        clip-path: url(#clippath-1);
      }

      .cls-24 {
        clip-path: url(#clippath-4);
      }

      .cls-25 {
        clip-path: url(#clippath-3);
      }

      .cls-26 {
        clip-path: url(#clippath-2);
      }

      .cls-27 {
        clip-path: url(#clippath-7);
      }

      .cls-28 {
        clip-path: url(#clippath-8);
      }

      .cls-29 {
        clip-path: url(#clippath-6);
      }

      .cls-30 {
        clip-path: url(#clippath-5);
      }

      .cls-12 {
        fill: #4285f4;
      }

      .cls-13 {
        fill: #ed8803;
      }

      .cls-14 {
        fill: #cf3300;
      }

      .cls-15 {
        fill: #c62e26;
      }

      .cls-16 {
        fill: #fff;
      }

      .cls-17 {
        fill: #f29500;
      }

      .cls-18 {
        fill: #f0d0b4;
      }

      .cls-19 {
        fill: #2b69b2;
      }

      .cls-20 {
        fill: #db4437;
      }
    </style>
    <clipPath id="clippath">
      <path class="cls-4" d="M18.5,219h409c10.1,0,18.5-7.1,18.5-15.8V15.8c0-8.7-8.3-15.8-18.5-15.8H18.5C8.3,0,0,7.1,0,15.8v187.4c0,8.7,8.3,15.8,18.5,15.8Z"/>
    </clipPath>
    <clipPath id="clippath-1">
      <rect class="cls-4" x="65.4" y="-298.4" width="416.8" height="268.6"/>
    </clipPath>
    <clipPath id="clippath-2">
      <rect class="cls-4" x="65.4" y="-298.4" width="416.8" height="268.6"/>
    </clipPath>
    <clipPath id="clippath-3">
      <rect class="cls-4" x="138.5" y="-233.8" width="319.8" height="177.7"/>
    </clipPath>
    <clipPath id="clippath-4">
      <path class="cls-4" d="M438.1-56.1H158.7c-11.2,0-20.2-9.1-20.2-20.2h0v-137.2c0-11.2,9.1-20.2,20.2-20.2h279.4c11.2,0,20.2,9.1,20.2,20.2h0V-76.3c0,11.2-9.1,20.2-20.2,20.2h0"/>
    </clipPath>
    <radialGradient id="radial-gradient" cx="-174.7" cy="534.7" fx="-174.7" fy="534.7" r="1.1" gradientTransform="translate(56189.3 94863.2) scale(319.8 -177.7)" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#fff"/>
      <stop offset=".4" stop-color="#fff"/>
      <stop offset="1" stop-color="#000"/>
    </radialGradient>
    <clipPath id="clippath-5">
      <rect class="cls-4" x="138.5" y="-233.8" width="319.8" height="177.7"/>
    </clipPath>
    <clipPath id="clippath-6">
      <path class="cls-4" d="M438.1-56.1H158.7c-11.2,0-20.2-9.1-20.2-20.2h0v-137.2c0-11.2,9.1-20.2,20.2-20.2h279.4c11.2,0,20.2,9.1,20.2,20.2h0V-76.3c0,11.2-9.1,20.2-20.2,20.2h0"/>
    </clipPath>
    <clipPath id="clippath-7">
      <path class="cls-4" d="M160.5-233.8h275.7c12.2,0,22.1,9.9,22.1,22.1V-78.2c0,12.2-9.9,22.1-22.1,22.1H160.5c-12.2,0-22.1-9.9-22.1-22.1t0,0v-133.5c0-12.2,9.9-22.1,22.1-22.1Z"/>
    </clipPath>
    <clipPath id="clippath-8">
      <rect class="cls-4" x="65.4" y="-298.4" width="416.8" height="268.6"/>
    </clipPath>
  </defs>
  <g id="Layer_1-2" data-name="Layer 1-2">
    <g>
      <g class="cls-21">
        <g>
          <path class="cls-14" d="M170.2-19.1c96.9,0,193.9,0,290.8,0,3,0,3.7.5,3.7,2.6-.1,58.9,0,117.9,0,176.8-1.5-.4-3-.8-4.4-1.3-7.5-2.8-14.7-5.8-22-8.8-14.7-5.9-28.9-12.3-42.7-19.2-16.5-8.2-32.4-17-48.1-26-18.8-10.8-36.5-22.3-53.9-34.2-7.4-5.1-14.6-10.3-21.8-15.6-13.4-9.7-26.9-19.3-39.9-29.3-8.2-6.3-16.5-12.5-24.8-18.6-9.3-6.8-18.4-13.8-28.5-20.1-3-1.9-6.1-3.7-8.4-6.1h0Z"/>
          <path class="cls-6" d="M280.1,235.6H-26.3V58.5c1.1.3,2.4.4,3.4.8,22,8,43.7,16.4,64.2,26.3,15,7.3,29.3,15.3,43.3,23.6,14.9,8.9,29.3,18.3,43.4,28,20.9,14.3,41.5,28.9,62.3,43.4,1.7,1.2,3.7,2.2,5.6,3.2.4,1.5,2.1,2.4,3.6,3.3,9.5,5.7,18.2,12,27.6,17.7,13.4,8.1,26.6,16.4,40.8,23.8,4.2,2.2,8.8,4,12.2,6.9h0Z"/>
          <path class="cls-7" d="M25-19.1h34.5c.2,1.3,1.6,1.8,3.1,2.4,9.9,3.7,19.8,7.5,29.6,11.3,9.1,3.6,18,7.5,27,11.2,19.6,8.2,38.6,17.1,57.1,26.5,18.5,9.4,36.4,19.4,54,29.7,25.3,14.7,49.5,30.3,73.4,46.1,20.3,13.4,40,27.3,59.7,41.2,13.6,9.6,27.1,19.3,40.7,28.9,18.8,13.3,37.5,26.8,56.2,40.2,1.3.9,2.3,2.2,4.4,2.3v13.2c-6.6-.5-11.7-3.6-17.4-5.5-13.4-4.6-26.6-9.6-39.8-14.6-12.4-4.6-24.9-9.1-37.1-14.1-12.7-5.2-25.4-10.6-38-15.9-14.4-6.1-28.2-12.7-41.3-20.1-18.4-10.4-34.8-22.3-49-35.7-13.5-12.9-27.1-25.8-40.9-38.5-11.6-10.8-24.2-21.1-37.4-31-12.1-9.1-24.9-17.6-38.2-25.7-8-4.9-15.8-9.9-24.3-14.3-9.5-4.9-18.8-10-28.6-14.7-13.7-6.5-27.1-13.2-41.4-19-2.4-1-5-1.8-6.4-3.7h0Z"/>
          <path class="cls-11" d="M25-19.1c1.4,1.9,4.1,2.7,6.4,3.7,14.3,5.8,27.7,12.5,41.4,19,9.8,4.7,19.1,9.8,28.6,14.7,8.5,4.4,16.3,9.5,24.3,14.3,13.3,8.1,26.2,16.6,38.2,25.7,13.1,9.9,25.7,20.2,37.4,31,13.8,12.8,27.3,25.6,40.9,38.5,14.1,13.5,30.5,25.4,49,35.7,13.1,7.4,27,14,41.3,20.1,12.6,5.4,25.2,10.7,38,15.9,12.2,5,24.7,9.5,37.1,14.1,13.2,4.9,26.4,9.9,39.8,14.6,5.7,2,10.8,5,17.4,5.5.7,2-1.1,1.7-2.8,1.7-35.7,0-71.4,0-107.1,0-2.8-2.9-7.3-4.2-11-6.1-18.1-9.6-35.6-19.7-51.8-31.1-12.6-8.9-25-17.9-36.5-27.6-10.4-8.7-20.2-17.7-30.2-26.6-9.8-8.8-18.9-18-28.9-26.7-12.8-11.1-25.9-22-41.1-31.6-21.1-13.3-43.9-24.6-68.2-34.6-19.2-7.9-38.7-15.3-58.7-22.1C10,23-8.1,16.5-26.3,10.2c0-9.2,0-18.4,0-27.6,0-1.4.5-1.8,2.5-1.8,16.3,0,32.6,0,48.9,0Z"/>
          <path class="cls-3" d="M464.7,220.6c-2.1-.2-3.1-1.4-4.4-2.3-18.7-13.4-37.4-26.9-56.2-40.2-13.6-9.6-27-19.3-40.7-28.9-19.7-13.9-39.4-27.8-59.7-41.2-23.9-15.8-48.1-31.4-73.4-46.1-17.6-10.2-35.5-20.3-54-29.7-18.5-9.4-37.5-18.3-57.1-26.5-9-3.8-17.9-7.6-27-11.2-9.8-3.9-19.7-7.6-29.6-11.3-1.5-.6-2.8-1.1-3.1-2.4h110.7c2.2,2.4,5.4,4.3,8.4,6.1,10,6.3,19.2,13.3,28.5,20.1,8.4,6.1,16.7,12.4,24.8,18.6,13,10,26.6,19.6,39.9,29.3,7.2,5.2,14.4,10.5,21.8,15.6,17.4,11.9,35.1,23.5,53.9,34.2,15.7,9,31.6,17.8,48.1,26,13.8,6.9,28,13.3,42.7,19.2,7.3,2.9,14.5,6,22,8.8,1.4.5,2.9.9,4.4,1.3v60.4h0Z"/>
          <path class="cls-10" d="M343.8,229.4c-18.1-9.6-35.6-19.7-51.8-31.1-12.6-8.9-25-17.9-36.5-27.6-10.4-8.7-20.2-17.7-30.2-26.6-9.8-8.8-18.9-18-28.9-26.7-12.8-11.1-25.9-22-41.1-31.6-21.1-13.3-43.9-24.6-68.2-34.6-19.2-7.9-38.7-15.3-58.7-22.1C10,23-8.1,16.5-26.3,10.2v48.3c1.1.3,2.4.4,3.4.8,22,8.1,43.7,16.4,64.2,26.3,15,7.3,29.3,15.3,43.3,23.6,14.9,8.9,29.3,18.3,43.4,28,20.9,14.3,41.5,28.9,62.3,43.4,1.7,1.2,3.7,2.2,5.6,3.2.4,1.5,2.1,2.4,3.6,3.3,9.5,5.7,18.2,12,27.6,17.7,13.4,8.1,26.6,16.4,40.8,23.8,4.2,2.2,8.8,4,12.2,6.9h74.6c-2.8-2.9-7.3-4.2-11-6.1h0Z"/>
        </g>
      </g>
      <g id="Group_67420" data-name="Group 67420">
        <path id="Path_172741" data-name="Path 172741" class="cls-16" d="M46.9,55.6c0-1.2-1-2.1-2.1-2.1s-2.1,1-2.1,2.1,1,2.1,2.1,2.1,2.1-1,2.1-2.1h0"/>
        <path id="Path_172742" data-name="Path 172742" class="cls-16" d="M32.3,55.6c0,1.2,1,2.1,2.1,2.1s2.1-1,2.1-2.1-1-2.1-2.1-2.1h0c-1.2,0-2.1,1-2.1,2.1"/>
        <path id="Path_172743" data-name="Path 172743" class="cls-16" d="M23.4,33l4.6,1.9,2.1,16.2c.1.8.8,1.3,1.5,1.3h16.6c.7,0,1.3-.6,1.3-1.3s-.6-1.3-1.3-1.3h-15.2l-.3-2.6h15.4c.5,0,1-.3,1.2-.8l3.7-8.9c.3-.7,0-1.4-.7-1.7-.2,0-.3-.1-.5-.1h-20.6l-.2-1.6c0-.5-.4-1-.9-1.2l-5.6-2.3c-.7-.3-1.4,0-1.8.6-.3.7,0,1.4.7,1.7,0,0,0,0,0,0M46.4,38.4h3.1l-2.6,6.2h-3.1l2.6-6.2h0ZM40.3,38.4h3.1l-2.6,6.2h-3.1l2.6-6.2ZM37.2,38.4l-2.6,6.2h-2.3l-.8-6.2h5.7Z"/>
        <path id="Path_172744" data-name="Path 172744" class="cls-16" d="M132.9,36c-4.5.2-7.9,4.1-7.7,8.5.2,4.2,3.5,7.5,7.7,7.7,2.1,0,4.2-.5,6.1-1.5.7-.4,1-1.2.6-1.9-.1-.2-.3-.4-.5-.5-.4-.3-1-.3-1.5,0-1.4.8-3,1.3-4.7,1.3-2.2-.2-4-1.8-4.3-4h10.6c.8,0,1.4-.6,1.4-1.4h0c.1-4.4-3.3-8-7.7-8.1M128.6,42.8c.2-2.4,2.3-4.1,4.7-4,2.1.2,3.8,1.8,3.9,4h-8.6Z"/>
        <path id="Path_172745" data-name="Path 172745" class="cls-16" d="M70.2,36.4h-9.7c-.7,0-1.3.6-1.3,1.3s.6,1.3,1.3,1.3h3.3v11.3c0,.8.7,1.5,1.5,1.5s1.5-.7,1.5-1.5v-11.3h3.3c.7,0,1.3-.6,1.3-1.3s-.6-1.3-1.3-1.3"/>
        <path id="Path_172746" data-name="Path 172746" class="cls-16" d="M106.7,36.4c-.8,0-1.5.7-1.5,1.5v12.3c0,.8.7,1.5,1.5,1.5h6.4c.7,0,1.3-.6,1.3-1.3s-.6-1.3-1.3-1.3h-4.9v-11.3c0-.9-.7-1.5-1.5-1.5"/>
        <path id="Path_172747" data-name="Path 172747" class="cls-16" d="M119,38c0-.9-.7-1.5-1.6-1.5s-1.5.7-1.5,1.5v12.3c0,.8.7,1.5,1.5,1.5h6.4c.7,0,1.3-.6,1.3-1.3s-.6-1.3-1.3-1.3h-4.9v-11.3h0Z"/>
        <path id="Path_172748" data-name="Path 172748" class="cls-16" d="M95.1,52.2c4.5,0,8.1-3.6,8.1-8.1s-3.6-8.1-8.1-8.1-8.1,3.6-8.1,8.1h0c0,4.5,3.6,8.1,8.1,8.1M95.1,38.8c2.9-.3,5.6,1.9,5.8,4.8s-1.9,5.6-4.8,5.8c-2.9.3-5.6-1.9-5.8-4.8,0-.2,0-.3,0-.5-.1-2.8,2-5.2,4.9-5.3"/>
        <path id="Path_172749" data-name="Path 172749" class="cls-16" d="M74.7,51.8c.8,0,1.5-.7,1.5-1.5v-3.9h3.1l3.4,4.8c.5.7,1.4.9,2.1.4.7-.5.9-1.4.4-2.1,0,0,0,0,0,0l-2.5-3.6c2.5-1.2,3.5-4.2,2.3-6.7-.8-1.7-2.6-2.8-4.5-2.8h-5.8c-.8,0-1.5.7-1.5,1.5v12.3c0,.8.7,1.5,1.5,1.5M76.2,39h3.8c1.3,0,2.3,1.1,2.3,2.4,0,1.3-1,2.3-2.3,2.3h-3.8v-4.7Z"/>
        <path id="Path_172750" data-name="Path 172750" class="cls-16" d="M153.9,36.7c-.7-.5-1.7-.3-2.1.4l-4,5.7-4-5.7c-.5-.7-1.4-.9-2.1-.4-.7.5-.9,1.4-.4,2.1,0,0,0,0,0,0l5,7.1v4.4c0,.8.7,1.6,1.5,1.6.9,0,1.6-.7,1.6-1.5h0v-4.4l5-7.1c.5-.7.3-1.7-.4-2.1h0"/>
      </g>
    </g>
  </g>
  <g id="Cyber_Monday_flat_4" data-name="Cyber Monday flat 4">
    <g id="_27_Gift" data-name=" 27 Gift">
      <path id="Path_720" data-name="Path 720" class="cls-5" d="M393.5,46.7h36v27h-36v-14s0-13,0-13Z"/>
      <path id="Path_721" data-name="Path 721" class="cls-17" d="M402.5,69.7h-9s0,3,0,3h36s0-27,0-27h-3c0,13.3-10.7,24-24,24Z"/>
      <path id="Path_722" data-name="Path 722" class="cls-17" d="M429.5,48.7h-36v-2h36v2Z"/>
      <path id="Path_723" data-name="Path 723" class="cls-20" d="M414.5,72.7h-6v-26h6v26Z"/>
      <path id="Path_724" data-name="Path 724" class="cls-15" d="M414.5,66.5c-1.9,1.1-3.9,1.9-6,2.5v3.8s6,0,6,0v-6.2Z"/>
      <path id="Path_725" data-name="Path 725" class="cls-15" d="M414.5,48.7h-6v-2h6v2Z"/>
      <path id="Path_726" data-name="Path 726" class="cls-20" d="M417.5,33.7v5h-10v-5c0-2.8,2.2-5,5-5s5,2.2,5,5Z"/>
      <path id="Path_727" data-name="Path 727" class="cls-5" d="M417.5,33.7v5h-10v-5c0-2.8,2.2-5,5-5s5,2.2,5,5Z"/>
      <path id="Path_728" data-name="Path 728" class="cls-9" d="M417.5,33.7v5h-10v-5c0-2.8,2.2-5,5-5s5,2.2,5,5Z"/>
      <ellipse id="Ellipse_24" data-name="Ellipse 24" class="cls-20" cx="402.5" cy="33.7" rx="5.2" ry="8.4" transform="translate(94.1 294.5) rotate(-45)"/>
      <path id="Path_729" data-name="Path 729" class="cls-9" d="M404.1,35.3c-2.7-2.7-6.1-3.9-8.4-3,.5,2,1.6,3.8,3.1,5.2,2.7,2.7,6.1,3.9,8.4,3-.5-2-1.6-3.8-3.1-5.2Z"/>
      <ellipse id="Ellipse_25" data-name="Ellipse 25" class="cls-20" cx="421.5" cy="33.7" rx="8.4" ry="5.2" transform="translate(99.6 307.9) rotate(-45)"/>
      <path id="Path_730" data-name="Path 730" class="cls-9" d="M419.9,35.3c2.7-2.7,6.1-3.9,8.4-3-.5,2-1.6,3.8-3.1,5.2-2.7,2.7-6.1,3.9-8.4,3,.5-2,1.6-3.8,3.1-5.2Z"/>
      <path id="Path_731" data-name="Path 731" class="cls-5" d="M397.5,46.7h-8v-8h44v8h-30"/>
      <path id="Path_732" data-name="Path 732" class="cls-20" d="M416.5,46.7h-10v-8h10v8Z"/>
      <path id="Path_733" data-name="Path 733" class="cls-18" d="M416.5,72.7h-15.4s0,0,0,0l-7.4-8.1c-2-2.2-5.5-2.5-7.8-.6,0,0,0,0,0,0-.3.3-.4.8,0,1.1l10.8,12.7c.1.1.3.2.4.3l26.5,8.6h12s0-17,0-17h-2s-5-5-5-5h-13.9c-2.2,0-4,1.8-4,4h0c0,2.2,1.8,4,4,4h5.9"/>
      <path id="Path_734" data-name="Path 734" class="cls-2" d="M385.8,64s0,0,0,0c-.3.3-.4.8,0,1.1l10.8,12.7c.1.1.3.2.4.3l26.5,8.6h12s0-2,0-2h-12s-26.5-8.6-26.5-8.6c-.2,0-.3-.2-.4-.3l-10.3-12.1c-.1,0-.3.2-.4.3Z"/>
      <path id="Path_735" data-name="Path 735" class="cls-12" d="M443.5,88.7h-8v-21h8v7s0,14,0,14Z"/>
      <path id="Path_736" data-name="Path 736" class="cls-19" d="M440.5,88.7h3s0-21,0-21h-3s0,7,0,7v14Z"/>
      <g id="Group_397" data-name="Group 397">
        <path id="Path_737" data-name="Path 737" class="cls-20" d="M386.5,43.7h-5v-2h5v2Z"/>
        <path id="Path_738" data-name="Path 738" class="cls-20" d="M385.8,40.4l-3.5-3.5,1.4-1.4,3.5,3.5-1.4,1.4Z"/>
        <path id="Path_739" data-name="Path 739" class="cls-20" d="M383.7,49.9l-1.4-1.4,3.5-3.5,1.4,1.4-3.5,3.5Z"/>
        <path id="Path_740" data-name="Path 740" class="cls-20" d="M441.5,43.7h-5v-2h5v2Z"/>
        <path id="Path_741" data-name="Path 741" class="cls-20" d="M439.3,49.9l-3.5-3.5,1.4-1.4,3.5,3.5-1.4,1.4Z"/>
        <path id="Path_742" data-name="Path 742" class="cls-20" d="M437.2,40.4l-1.4-1.4,3.5-3.5,1.4,1.4-3.5,3.5Z"/>
      </g>
    </g>
  </g>
  <g id="Group_394" data-name="Group 394">
    <g class="cls-23">
      <g id="Group_393" data-name="Group 393">
        <g id="Group_388" data-name="Group 388">
          <g class="cls-26">
            <g id="Group_387" data-name="Group 387">
              <path id="Path_712" data-name="Path 712" class="cls-16" d="M438.1-56.1H158.7c-11.2,0-20.2-9.1-20.2-20.2v-137.2c0-11.2,9.1-20.2,20.2-20.2h279.4c11.2,0,20.2,9.1,20.2,20.2h0V-76.3c0,11.2-9.1,20.2-20.2,20.2h0"/>
              <g id="Group_381" data-name="Group 381" class="cls-22">
                <g id="Group_380" data-name="Group 380">
                  <g class="cls-25">
                    <g id="Group_379" data-name="Group 379">
                      <g id="Group_378" data-name="Group 378">
                        <g class="cls-24">
                          <g id="Group_377" data-name="Group 377">
                            <rect id="Rectangle_83" data-name="Rectangle 83" class="cls-8" x="138.5" y="-233.8" width="319.8" height="177.7"/>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
              <g id="Group_386" data-name="Group 386" class="cls-22">
                <g id="Group_385" data-name="Group 385">
                  <g class="cls-30">
                    <g id="Group_384" data-name="Group 384">
                      <g id="Group_383" data-name="Group 383">
                        <g class="cls-29">
                          <g id="Group_382" data-name="Group 382">
                            <rect id="Rectangle_85" data-name="Rectangle 85" class="cls-8" x="138.5" y="-233.8" width="319.8" height="177.7"/>
                          </g>
                        </g>
                      </g>
                    </g>
                  </g>
                </g>
              </g>
            </g>
          </g>
        </g>
        <g id="Group_390" data-name="Group 390">
          <g class="cls-27">
            <g id="Group_389" data-name="Group 389">
              <path id="Path_715" data-name="Path 715" class="cls-1" d="M142.7-111.4c33.6-8.3,70.1-.7,102.8-11.8,17.8-6.1,33.3-17.3,44.7-32.3,7.3-9.7,12.6-23.6,5.8-33.6,7.2,5,13.3,11.3,18,18.7,1,1.4,1.7,3,1.7,4.7-.3,6.1-10.2,5.1-14.5,9.4-3.2,3.2-2.3,9,1,12s8.4,3.5,12.8,2.6c15.3-3.4,22.7-20.9,24.9-36.4,2.4-16.7,1.6-33.6-2.1-50.1-.7-3.1-1.5-6.3-.8-9.4,2.8-11.6,22.7-9.8,27.5-20.6,2-4.5.7-9.8,2.4-14.4,1.1-2.7,3.1-5,5.2-7.1l15.4-16.1c1-1.1,2.1-2.2,3.6-2.3,1.6-.2,3.1.8,4.3,1.8,20.8,16.7,62.8-3.8,77.5,18.4,18.4,28,5.3,171.9-1.3,189.2-1.9,5,.9,19-2.6,23-5.4,6.1-36.6,30-40.3,32.1-2.3,1.3-35-18.9-37.6-18.8-73.4,3.7-144,19.1-217.5,21.5-25.4.8-51-2.5-76.3,0-11.1,1.1-33,5.6-31.7-11.4.7-9.4,8.7-18.3,14-25.7,15.4-21.4,37.8-36.7,63.3-43.2"/>
              <path id="Path_716" data-name="Path 716" class="cls-1" d="M308.5-198.1c-2-1.8-4.3-3.1-6.4-4.9-7-6.1-8.7-16.4-3.8-24.3-.4,3.4,0,6.8,1.3,9.9,1,2.5,2.9,5,5.6,5.2,2.6.2,4.8-1.8,6.3-3.9,1,1.6,1.9,3.4,2.4,5.3.6,1.9.4,3.9-.5,5.7-.4.7-.8,1.2-1.2,1.9-1,2.2,1.4,8.5-.6,9.6-1.1-1.5-1.8-3.1-3.2-4.5"/>
              <path id="Path_717" data-name="Path 717" class="cls-13" d="M232.8-99.1c10.3-.8,21.6-2.5,28.3-10.4-9.7,12.7-23.2,21.9-38.5,26.5,5.5,1.7,11.5,1.5,16.9-.6-3.3,3.2-7.4,5.6-11.9,6.8-.1,4.4,2.9,8.4,6.6,10.7s8.2,3.1,12.5,3.7c5.8,1,11.6,1.3,17.5.8,13.9-1.4,26.5-9.6,40.5-10.2,2.7-.2,5.4.2,7.9,1.1,4.8,1.9,7.9,6.4,12.1,9.3,14.5,9.8,36.3-2.1,50.8,7.6-15.9,8.8-35,8.5-53.2,9.1-34.8,1.3-69.9,7.2-104.2,1.7-10-1.6-19.9-4.2-29.9-4.9-6.2-.5-12.6-.2-18.6-2-6-1.8-11.3-5.7-17.5-7.1-5.4-1.2-11.4.7-16.6-1.5-6.7-2.9-8.9-10.3-7.9-17.1,3.4-24.3,38.4-21.1,56.3-21.8,16.3-.7,32.6-.7,48.9-1.9"/>
              <path id="Path_718" data-name="Path 718" class="cls-13" d="M362.6-215.3c.8,8.3,1,16.6.5,24.9,2.8-9.8,2.5-20.2,2.2-30.4.7,3.7,1.4,7.4,2.2,11,1.2-5.2,2.1-10.5,2.8-15.8-.2,2.4-.2,4.8.3,7.1.7-3.9,1.6-7.9,3.8-11.2s6.1-5.7,10-5.2c-5.8-3.7-12.7-5.5-19.6-5.2-2.1.1-5.3.4-7,1.8-2,1.8-2,2.5-.6,4.5,3.7,5.5,4.9,12.6,5.5,18.3"/>
              <path id="Path_719" data-name="Path 719" class="cls-13" d="M307.5-174c.2,1.4,0,2.8-.4,4.2-.3.7-.8,1.4-1.3,2-.7.8-1.4,1.5-2.2,2.1-1.8,1.5-3.8,2.6-5.4,4.4-1.7,1.9-2.7,4.4-2.8,6.9-.1,1.3.2,2.7.9,3.9,0-1.1.1-2.2.4-3.3.7-1.5,1.8-2.8,3.2-3.7,2-1.4,4.2-2.4,6.5-3,2-.5,4.1-.8,5.7-2.2,1.3-1.2,1.9-3,1.6-4.7-.2-1-.6-1.9-1.2-2.8-.9-1.6-1.9-3.3-3-4.8-.5-.8-1.1-1.5-1.6-2.3-.4-.5-1-1.7-1.6-1.8.5,1.7.9,3.4,1.2,5.2"/>
            </g>
          </g>
        </g>
        <g id="Group_392" data-name="Group 392">
          <g class="cls-28">
            <g id="Group_391" data-name="Group 391">
              <rect id="Rectangle_89" data-name="Rectangle 89" class="cls-1" x="138.5" y="-211" width="4.4" height="55.6"/>
            </g>
          </g>
        </g>
      </g>
    </g>
  </g>
</svg>
```

## File: src/modules/loyalty/components/cashier-view/client-phone-input.vue
```vue
<template>
  <v-sheet class="pa-0 mb-2 loyalty-sheet" color="transparent" width="100%">
    <v-chip
      class="w-100 pa-0 phone-chip"
      prepend-icon="mdi mdi-barcode"
      rounded="lg"
      variant="text"
    >
      <template #append>
        <v-icon color="primary" @click.stop="emit('openKeyboard')">
          mdi mdi-keyboard
        </v-icon>
      </template>
      {{ t('scan_costumer_card') }}
    </v-chip>
    <v-otp-input
      v-model="phone"
      :length="8"
      class="pa-0"
      height="30"
      label="scan_costumer_card"
      max-width="none"
      type="number"
      variant="outlined"
      @finish="fetchCustomerByPhone"
    >
    </v-otp-input>
  </v-sheet>
</template>
⋮----
<template #append>
        <v-icon color="primary" @click.stop="emit('openKeyboard')">
          mdi mdi-keyboard
        </v-icon>
      </template>
{{ t('scan_costumer_card') }}
⋮----
<script lang="ts" setup>
import { computed } from 'vue';
import { useCustomer } from '../../../../store/customer/state';
import { fetchCustomerDetails } from '../../../../store/customer/actions';
import { useI18n } from 'vue-i18n';
const emit = defineEmits(['openKeyboard']);
const { t } = useI18n();
const customerState = useCustomer();
const phone = computed({
  get: () => customerState.customerPhone,
  set: (val: string) => {
    customerState.customerPhone = val;
  }
});
const fetchCustomerByPhone = () => {
  console.log('getting customer details ', phone.value);
  fetchCustomerDetails({ phone: Number(phone.value) });
};
</script>
<style>
.loyalty-card .v-card-item {
  border-bottom: solid 1px #ccc;
  margin-bottom: 5px;
}
.loyalty-card .v-card-title {
  font-size: 1em;
  margin-bottom: 0 !important;
}
.loyalty-card .rm-loyalty {
  position: absolute;
  top: 6px;
  right: 10px;
}
.loyalty-sheet {
  margin-top: -8px;
}
.loyalty-card .v-otp-input__content {
  padding: 0 !important;
}
.phone-chip .v-chip__append {
  position: absolute;
  right: 0;
}
</style>
```

## File: src/modules/loyalty/components/cashier-view/loyalty-card.vue
```vue
<template>
  <v-card
    :prepend-icon="customer?.phone ? 'mdi-account' : ''"
    :title="customer?.name"
    class="bg-grey-lighten-3 pa-2 loyalty-card"
    variant="flat"
  >
    <v-btn
      v-if="customer"
      class="rm-loyalty"
      color="error"
      size="x-small"
      variant="flat"
      @click="publish('remove-customer')"
    >Remove
    </v-btn>
    <ClientPhoneInput v-if="!customer" @openKeyboard="emit('openKeyboard')" />
    <LoyaltySummary
      :points="customer?.loyalty?.pointsBalance ?? 0"
      :value="customer?.loyalty?.pointsValue ?? 0"
    />
    <RedeemSlider
      v-if="customer"
      :max="customer.loyalty.pointsBalance"
      :points="customer.loyalty.pointsBalance"
    />
  </v-card>
</template>
<script lang="ts" setup>
import { useCustomer } from '../../../../store/customer/state';
import { publish } from '@enegix/events';
import RedeemSlider from './redeem-slider.vue';
import ClientPhoneInput from './client-phone-input.vue';
import LoyaltySummary from './loyalty-summary.vue';
import { computed } from 'vue';
const emit = defineEmits(['openKeyboard']);
const customerState = useCustomer();
const customer = computed(() => customerState.customer);
</script>
<style>
.loyalty-card .v-card-item {
  border-bottom: solid 1px #ccc;
  margin-bottom: 5px;
}
.loyalty-card .v-card-title {
  font-size: 1em;
  margin-bottom: 0 !important;
}
.loyalty-card .rm-loyalty {
  position: absolute;
  top: 6px;
  right: 10px;
}
</style>
```

## File: src/modules/loyalty/components/cashier-view/loyalty-header.vue
```vue
<template>
  <img :src="crownIcon" alt="loyalty card" width="20" />
</template>
<script lang="ts" setup>
import crownIcon from '../../assets/crown.svg?url';
</script>
```

## File: src/modules/loyalty/components/cashier-view/loyalty-membership.vue
```vue
<template>
  <customCard :img="true" title="loyalty_membership">
    <template #icon>
      <LoyaltyHeader />
    </template>
    <template #body>
      <LoyaltyCard @openKeyboard="showKeyboard = true" />
    </template>
  </customCard>
  <Teleport to="body">
    <SimpleKeyboard
      v-if="showKeyboard"
      v-model="customerPhone"
      @onKeyPress="onKeyPress"
    />
  </Teleport>
</template>
⋮----
<template #icon>
      <LoyaltyHeader />
    </template>
<template #body>
      <LoyaltyCard @openKeyboard="showKeyboard = true" />
    </template>
⋮----
<script lang="ts" setup>
import { computed, ref } from 'vue';
import LoyaltyHeader from './loyalty-header.vue';
import LoyaltyCard from './loyalty-card.vue';
import SimpleKeyboard from '../../../../components/simpleKeyboard.vue';
import { useCustomer } from '../../../../store/customer/state';
import { fetchCustomerDetails } from '../../../../store/customer/actions';
import CustomCard from '../../../../components/customs/customCard.vue';
const showKeyboard = ref(false);
const customerPhone = computed(() => useCustomer().customerPhone);
const onKeyPress = (button: string) => {
  if (button === '{downkeyboard}' || button === '{enter}') {
    fetchCustomerDetails({ phone: Number(customerPhone.value) });
    setTimeout(() => (showKeyboard.value = false), 200);
  }
};
</script>
```

## File: src/modules/loyalty/components/cashier-view/loyalty-summary.vue
```vue
<template>
  <div id="card-body" class="d-flex justify-space-between align-center">
    <div id="details">
      <p class="text-primary" style="font-size: 0.7rem">{{ t('loyalty_points').toUpperCase() }}</p>
      <div id="points-exchange" class="d-flex">
        <div id="available">
          <h3>{{ points }}</h3>
          <p class="text-inputColor" style="font-size: smaller">{{ t('available') }}</p>
        </div>
        <div class="mb-5 mx-3 compare-icon ">
          <compare-arrows />
        </div>
        <h3>{{ formatPrice(value) }} {{ t('KD') }}</h3>
      </div>
    </div>
    <v-btn color="#AF" variant="tonal">
      {{ t('apply') }} [ {{ formatPrice(loyalty.$state.amount) }} ]
    </v-btn>
  </div>
</template>
⋮----
<p class="text-primary" style="font-size: 0.7rem">{{ t('loyalty_points').toUpperCase() }}</p>
⋮----
<h3>{{ points }}</h3>
<p class="text-inputColor" style="font-size: smaller">{{ t('available') }}</p>
⋮----
<h3>{{ formatPrice(value) }} {{ t('KD') }}</h3>
⋮----
{{ t('apply') }} [ {{ formatPrice(loyalty.$state.amount) }} ]
⋮----
<script lang="ts" setup>
import { defineProps } from 'vue';
import { useI18n } from 'vue-i18n';
import { formatPrice } from '@trolley/utils';
import { useLoyaltyStore } from '../../store/loyalty-store';
import CompareArrows from '../../assets/compare-arrows.vue';
defineProps({
  points: {
    type: Number,
    required: true,
    default: 0
  },
  value: {
    type: Number,
    required: true,
    default: 0
  }
});
const { t } = useI18n();
const loyalty = useLoyaltyStore();
</script>
<style scoped>
.compare-icon {
  width: 25px;
}
</style>
```

## File: src/modules/loyalty/components/cashier-view/redeem-slider.vue
```vue
<script lang="ts" setup>
import { computed, defineProps, onMounted, ref } from 'vue';
import { useLoyaltyStore } from '../../store/loyalty-store';
import { BackendStatusTopic } from '../../../../features/app-mode/backend-status-topic';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
const loyalty = useLoyaltyStore();
const props = defineProps({
  min: {
    type: Number,
    default: 0
  },
  max: {
    type: Number,
    default: 0
  },
  value: Number
});
const maxPoints = computed(() => {
  return Math.min(
    usePendingTransactionStore().itemsManager.redeemableAmount /
    loyalty.redeem_factor,
    props.max
  );
});
const disabled = ref(true);
onMounted(() => {
  BackendStatusTopic.publish('CHECK');
  BackendStatusTopic.subscribe('STATUS', (mode) => {
    disabled.value = mode === 'OFFLINE';
  });
});
</script>
<template>
  <v-slider
    v-model="loyalty.points"
    :disabled="disabled"
    :max="maxPoints"
    :min
    :step="loyalty.step"
    class="align-center"
    color="primary"
    hide-details
    @end="
      usePendingTransactionStore().itemsManager.setRedeemedAmount(
        useLoyaltyStore().amount,
      )
    "
  >
  </v-slider>
</template>
```

## File: src/modules/loyalty/components/client-view/client-loyalty-card.vue
```vue
<script lang="ts" setup>
import userPng from '../../../../assets/images/login/user.png?url';
import { formatPrice } from '@trolley/utils';
import { z } from 'zod';
import type { Customer } from '../../../../store/customer/types';
const customerSchema = z
  .object({
    name: z.string(),
    loyalty: z.object({
      pointsBalance: z.number().nonnegative(),
      pointsValue: z.number().nonnegative(),
      earn_factor: z.number().nonnegative(),
      redeem_factor: z.number().nonnegative(),
    }),
  })
  .nullable();
const props = defineProps<{
  customer: Customer | null;
}>();
const parsedCustomer = customerSchema.safeParse(props.customer);
if (!parsedCustomer.success) {
  console.error('Invalid customer prop:', parsedCustomer.error);
}
const customer = parsedCustomer.data;
</script>
<template>
  <div class="authMembershipCard">
    <div v-if="customer" class="loyaltyPoints text-white text">
      <h4>LOYALTY POINTS</h4>
      <div class="d-flex align-center flex-row ga-4 text-white">
        <p>{{ customer.loyalty.pointsBalance }}</p>
        <span class="mdi mdi-compare-horizontal" />
        <p>{{ formatPrice(customer.loyalty.pointsValue) }} KD</p>
      </div>
    </div>
    <div v-else class="loyaltyPoints text-white text">
      <h4>No Loyalty Points</h4>
      <p>Please log in to see your loyalty points.</p>
    </div>
    <div class="customerDetailsWrapper">
      <v-avatar :image="userPng" class="avatar" size="34" />
      <div class="customerDetails">
        <p class="text">{{ customer ? customer.name : 'Guest' }}</p>
      </div>
    </div>
  </div>
</template>
⋮----
<p>{{ customer.loyalty.pointsBalance }}</p>
⋮----
<p>{{ formatPrice(customer.loyalty.pointsValue) }} KD</p>
⋮----
<p class="text">{{ customer ? customer.name : 'Guest' }}</p>
⋮----
<style scoped>
.authMembershipCard {
  min-width: 95%;
  padding-top: 50%;
  background-image: url('../../assets/loyality-card-01.svg');
  background-size: contain;
  position: relative;
}
.customerDetails {
  position: absolute;
  left: 9%;
  bottom: 11.7%;
  font-size: 10px;
  background-color: white;
  width: fit-content;
  padding: 4px 24px;
  font-weight: 500;
  border-radius: 8px;
}
.avatar {
  position: absolute;
  left: 4%;
  bottom: 9%;
  z-index: 1;
  background-color: white;
  padding: 7px;
}
.loyaltyPoints {
  position: absolute;
  right: 3%;
  bottom: 10%;
}
.loyaltyPoints h4 {
  font-size: 12px;
  text-transform: uppercase;
}
.loyaltyPoints p {
  font-size: 16px;
  font-weight: bold;
}
.text {
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
</style>
```

## File: src/modules/loyalty/components/client-view/client-membership.vue
```vue
<script setup lang="ts">
import shoppingIcon from '../../../../assets/icons/shopping-icon.svg';
import { computed, ref } from 'vue';
import { useCustomer } from '../../../../store/customer/state';
import NewCoupon from '../../../../components/newCoupon.vue';
import ClientLoyaltyCard from './client-loyalty-card.vue';
import { useI18n } from 'vue-i18n';
import ClientUnAuthLoyaltyCard from './client-unAuth-loyalty-card.vue';
import { useLoyaltyStore } from '../../store/loyalty-store';
const tab = ref('my_points');
const { t, locale } = useI18n();
const customerCoupons = computed(() => useCustomer()?.customer?.discounts);
</script>
<template>
  <div class="d-flex justify-center align-center flex-column mb-2">
    <div v-if="useCustomer().isAuthed" class="w-100">
      <v-tabs
        bg-color="background"
        slider-color="transparent"
        selected-class="text-primary bg-white font-weight-bold"
        style="border-radius: 10px; padding: 5px; box-sizing: unset"
        fixed-tabs
        v-model="tab"
        v-if="useLoyaltyStore().is_loyalty_enabled"
      >
        <v-tab
          value="my_points"
          class="text-uppercase"
          style="border-radius: 10px"
        >
          {{ t('my_points') }}
          <template #prepend>
            <v-icon>mdi mdi-ticket-percent-outline</v-icon>
          </template>
        </v-tab>
        <v-tab value="my_coupons" class="text-uppercase"
          >{{ t('my_coupons') }}
          <template #prepend>
            <v-icon>mdi mdi-store</v-icon>
          </template>
        </v-tab>
      </v-tabs>
      <v-window
        v-if="useLoyaltyStore().is_loyalty_enabled"
        v-model="tab"
        class="tab w-100 mt-1"
      >
        <v-window-item value="my_points">
          <client-loyalty-card :customer="useCustomer().customer" />
        </v-window-item>
        <v-window-item value="my_coupons">
          <div
            class="d-flex flex-column align-content-start bg-grey-lighten-3x rounded-lg mt-2 coupons-wrapper"
          >
            <new-coupon
              v-for="(coupon, index) in customerCoupons"
              :key="index"
              :coupon="coupon"
              readonly
            />
          </div>
        </v-window-item>
      </v-window>
    </div>
    <div
      v-if="!useCustomer().isAuthed && useLoyaltyStore().is_loyalty_enabled"
      class="w-100"
    >
      <v-btn variant="tonal" color="primary w-100" height="45">
        <shoppingIcon />
        <p class="text-black ms-2 text">{{ t('open_trolly_&') }}</p>
      </v-btn>
      <client-un-auth-loyalty-card
        v-if="useLoyaltyStore().is_loyalty_enabled"
      />
    </div>
  </div>
</template>
⋮----
{{ t('my_points') }}
<template #prepend>
            <v-icon>mdi mdi-ticket-percent-outline</v-icon>
          </template>
⋮----
>{{ t('my_coupons') }}
<template #prepend>
            <v-icon>mdi mdi-store</v-icon>
          </template>
⋮----
<p class="text-black ms-2 text">{{ t('open_trolly_&') }}</p>
⋮----
<style scoped>
.tab {
  min-height: 215px;
}
.coupons-wrapper {
  min-height: 205px;
  overflow-y: scroll;
}
.text {
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
.membershipCard {
  min-width: 95%;
  padding-top: 50%;
  background-image: url('../../assets/loyality-card-01.svg');
  background-size: contain;
  position: relative;
}
.authMembershipCard {
  min-width: 95%;
  padding-top: 50%;
  background-image: url('../../assets/loyality-card-01.svg');
  background-size: contain;
  position: relative;
}
.customerDetails {
  position: absolute;
  left: 9%;
  right: 0;
  bottom: 11.7%;
  font-size: 10px;
  background-color: white;
  width: fit-content;
  padding: 4px 24px;
  font-weight: 500;
  border-radius: 8px;
}
.avatar {
  position: absolute;
  left: 4%;
  right: 0;
  bottom: 9%;
  z-index: 1;
  background-color: white;
  padding: 7px;
}
.loyaltyPoints {
  position: absolute;
  right: 3%;
  bottom: 10%;
}
.loyaltyPoints h4 {
  font-size: 12px;
  text-transform: uppercase;
}
.loyaltyPoints p {
  font-size: 16px;
  font-weight: bold;
}
.cart {
  position: absolute;
  top: 15%;
  left: 70%;
  right: 0;
  bottom: 0;
  background-image: url('../../../../assets/icons/membership/cart.svg');
}
.barcode {
  width: 150px;
  height: 60px;
  background-image: url('../../../../assets/icons/membership/barcode.svg');
}
.text-input {
  position: absolute;
  bottom: 0;
  left: 15px;
  right: 15px;
}
.phone-sheet {
  position: absolute;
  bottom: 0;
}
.v-otp-input {
  margin-top: -8px;
}
</style>
```

## File: src/modules/loyalty/components/client-view/client-unAuth-loyalty-card.vue
```vue
<template>
  <div class="membershipCard mt-3">
    <v-sheet class="phone-sheet" color="transparent">
      <v-chip
        class="w-100 text-capitalize font-weight-bold"
        color="white"
        prepend-icon="mdi mdi-barcode"
        rounded="lg"
        variant="text"
      >
        {{ t('click_here_&_scan_membership') }}
      </v-chip>
      <v-otp-input
        v-model="useCustomer().customerPhone"
        :length="8"
        class="pt-0"
        color="white"
        label="scan_costumer_card"
        max-width="none"
        type="number"
      />
    </v-sheet>
  </div>
</template>
⋮----
{{ t('click_here_&_scan_membership') }}
⋮----
<script lang="ts" setup>
import { useI18n } from 'vue-i18n';
import { useCustomer } from '../../../../store/customer/state';
const { t } = useI18n();
</script>
<style scoped>
.membershipCard {
  min-width: 95%;
  padding-top: 50%;
  background-image: url('../../assets/loyality-card-01.svg');
  background-size: contain;
  position: relative;
}
.loyaltyPoints h4 {
  font-size: 12px;
  text-transform: uppercase;
}
.loyaltyPoints p {
  font-size: 16px;
  font-weight: bold;
}
.phone-sheet {
  position: absolute;
  bottom: 0;
}
</style>
```

## File: src/modules/loyalty/store/loyalty-store.ts
```typescript
import { defineStore } from 'pinia';
import { subscribe } from '@enegix/events';
import { EMPLOYEE_REQUESTS } from '../../../features/usecases/employee/events';
import { AUTH_EVENTS } from '../../auth/events';
import { TRANSACTION_EVENTS } from '@trolley/transactions';
import { BackendStatusTopic } from '../../../features/app-mode/backend-status-topic';
import { ref, watch } from 'vue';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { useSettings } from '../../settings/store';
import { runAfterStoreHydrated } from '../../../utils/runAfterStoreHydrated';
⋮----
const reset = () =>
```

## File: src/modules/loyalty/tests/loyalty-store.spec.ts
```typescript
import { createPinia, setActivePinia } from 'pinia';
import { beforeEach, describe, expect, it, vi } from 'vitest';
import { useLoyaltyStore } from '../store/loyalty-store';
⋮----
type ItemsManager = {
  redeemableAmount: number;
  totalItems: number;
  setRedeemedAmount: ReturnType<typeof vi.fn>;
  setEarnPointsFactor: ReturnType<typeof vi.fn>;
};
type PendingTransactionStore = {
  itemsManager: ItemsManager;
};
const usePendingTransactionStore = ()
```

## File: src/modules/payments/assets/credit.svg
```
<svg height="511pt" viewBox="-17 1 511 511.999" width="511pt" xmlns="http://www.w3.org/2000/svg"><path d="m421.808594 189.621094-231.707032 231.703125c-10.46875 10.472656-27.445312 10.472656-37.917968 0l-136.347656-136.347657c-10.472657-10.472656-10.472657-27.449218 0-37.917968l231.703124-231.707032c10.472657-10.46875 27.449219-10.46875 37.917969 0l136.351563 136.351563c10.46875 10.46875 10.46875 27.445313 0 37.917969zm0 0" fill="#8cbafa"/><path d="m421.808594 151.703125-17.019532-17.019531c9.324219 9.324218 8.394532 25.371094-2.074218 35.84375l-231.707032 231.703125c-10.46875 10.472656-26.515624 11.402343-35.839843 2.078125l17.015625 17.015625c10.472656 10.472656 27.449218 10.472656 37.917968 0l231.707032-231.703125c10.46875-10.472656 10.46875-27.449219 0-37.917969zm0 0" fill="#5692d8"/><path d="m243.753906 68.164062-22.703125 22.703126c-8.929687 8.925781-8.929687 23.394531 0 32.320312 8.925781 8.925781 23.394531 8.925781 32.320313 0l22.703125-22.703125c8.925781-8.925781 8.925781-23.394531 0-32.320313-8.925781-8.925781-23.394531-8.925781-32.320313 0zm0 0" fill="#ffcd34"/><path d="m443.6875 258.050781h-327.679688c-14.808593 0-26.8125 12.003907-26.8125 26.808594v192.828125c0 14.808594 12.003907 26.8125 26.8125 26.8125h327.679688c14.804688 0 26.808594-12.003906 26.808594-26.8125v-192.828125c0-14.804687-12.003906-26.808594-26.808594-26.808594zm0 0" fill="#ffcd34"/><path d="m443.6875 258.050781h-24c14.804688 0 26.808594 12.003907 26.808594 26.808594v192.828125c0 14.808594-12.003906 26.8125-26.808594 26.8125h24c14.804688 0 26.808594-12.003906 26.808594-26.8125v-192.828125c0-14.804687-12.003906-26.808594-26.808594-26.808594zm0 0" fill="#e69012"/><path d="m89.195312 318.625h381.300782v46.324219h-381.300782zm0 0" fill="#575b7a"/><path d="m446.496094 318.625h24v46.324219h-24zm0 0" fill="#252d4c"/><path d="m376.78125 438.96875v28.570312c0 2.210938 1.789062 4 4 4h45.445312c2.210938 0 4-1.789062 4-4v-28.570312c0-2.210938-1.789062-4-4-4h-45.445312c-2.210938 0-4 1.789062-4 4zm0 0" fill="#e9e9ea"/><path d="m239.761719 438.96875v28.570312c0 2.210938 1.792969 4 4 4h96.121093c2.210938 0 4-1.789062 4-4v-28.570312c0-2.210938-1.789062-4-4-4h-96.121093c-2.207031 0-4 1.789062-4 4zm0 0" fill="#e9e9ea"/><path d="m21.140625 279.675781c-7.53125-7.53125-7.53125-19.785156 0-27.3125l183.785156-183.785156c2.929688-2.929687 2.929688-7.679687 0-10.605469-2.929687-2.933594-7.679687-2.929687-10.605469 0l-183.789062 183.785156c-13.375 13.375-13.375 35.144532 0 48.523438l46.292969 46.289062c1.460937 1.460938 3.382812 2.195313 5.300781 2.195313 1.921875 0 3.839844-.730469 5.304688-2.195313 2.929687-2.929687 2.929687-7.679687 0-10.605468zm0 0"/><path d="m168.578125 149.363281-113.492187 113.492188c-2.929688 2.929687-2.929688 7.679687 0 10.609375 1.464843 1.460937 3.382812 2.195312 5.304687 2.195312 1.917969 0 3.835937-.730468 5.300781-2.195312l113.492188-113.492188c2.929687-2.929687 2.929687-7.679687 0-10.609375-2.925782-2.925781-7.675782-2.925781-10.605469 0zm0 0"/><path d="m237.210938 137.371094c7.773437 0 15.546874-2.957032 21.464843-8.875l22.703125-22.703125c11.835938-11.835938 11.835938-31.09375 0-42.929688-11.835937-11.835937-31.09375-11.835937-42.929687 0l-22.703125 22.703125c-5.734375 5.734375-8.890625 13.355469-8.890625 21.464844 0 8.105469 3.15625 15.730469 8.890625 21.464844 5.917968 5.917968 13.691406 8.875 21.464844 8.875zm-10.859376-41.199219 22.703126-22.703125c5.988281-5.988281 15.730468-5.988281 21.714843 0 5.988281 5.988281 5.988281 15.730469 0 21.714844l-22.703125 22.703125c-5.984375 5.988281-15.726562 5.988281-21.714844 0-2.898437-2.898438-4.496093-6.753907-4.496093-10.855469s1.597656-7.960938 4.496093-10.859375zm0 0"/><path d="m443.683594 250.550781h-72.195313l55.625-55.625c13.378907-13.378906 13.378907-35.148437 0-48.527343l-136.351562-136.347657c-6.480469-6.480469-15.097657-10.050781-24.261719-10.050781s-17.78125 3.570312-24.265625 10.050781l-26.71875 26.71875c-2.925781 2.929688-2.925781 7.675781 0 10.605469 2.929687 2.929688 7.679687 2.929688 10.605469 0l26.722656-26.71875c3.644531-3.648438 8.496094-5.65625 13.65625-5.65625 5.15625 0 10.007812 2.007812 13.65625 5.65625l136.347656 136.347656c7.53125 7.53125 7.53125 19.78125 0 27.3125l-66.230468 66.230469h-189.535157l54.515625-54.515625c2.929688-2.925781 2.929688-7.675781 0-10.605469-2.929687-2.929687-7.679687-2.929687-10.605468 0l-65.121094 65.125h-23.519532c-18.921874 0-34.3125 15.390625-34.3125 34.308594v192.828125c0 18.917969 15.390626 34.3125 34.3125 34.3125h327.675782c18.921875 0 34.3125-15.394531 34.3125-34.3125v-27.71875c0-4.144531-3.355469-7.5-7.5-7.5-4.140625 0-7.5 3.355469-7.5 7.5v27.71875c0 10.648438-8.660156 19.3125-19.3125 19.3125h-327.675782c-10.648437 0-19.3125-8.664062-19.3125-19.3125v-105.238281h366.300782v47.519531c0 4.140625 3.355468 7.5 7.5 7.5 4.144531 0 7.5-3.359375 7.5-7.5v-135.105469c0-18.921875-15.390625-34.3125-34.3125-34.3125zm-327.675782 15h327.675782c10.648437 0 19.3125 8.664063 19.3125 19.3125v26.265625h-366.300782v-26.265625c0-10.648437 8.664063-19.3125 19.3125-19.3125zm-19.3125 91.898438v-31.320313h366.300782v31.320313zm0 0"/><path d="m380.78125 427.46875c-6.339844 0-11.5 5.160156-11.5 11.5v28.570312c0 6.34375 5.160156 11.5 11.5 11.5h45.445312c6.339844 0 11.5-5.15625 11.5-11.5v-28.570312c0-6.339844-5.160156-11.5-11.5-11.5zm41.945312 36.570312h-38.445312v-21.570312h38.445312zm0 0"/><path d="m243.761719 427.46875c-6.339844 0-11.5 5.160156-11.5 11.5v28.570312c0 6.34375 5.160156 11.5 11.5 11.5h96.121093c6.339844 0 11.5-5.15625 11.5-11.5v-28.570312c0-6.339844-5.160156-11.5-11.5-11.5zm92.621093 36.570312h-89.121093v-21.570312h89.121093zm0 0"/><path d="m152.691406 464.039062c-4.140625 0-7.5 3.359376-7.5 7.5 0 4.144532 3.359375 7.5 7.5 7.5h47.890625c4.140625 0 7.5-3.355468 7.5-7.5 0-4.140624-3.359375-7.5-7.5-7.5zm0 0"/></svg>
```

## File: src/modules/payments/assets/deliveroo.svg
```
<?xml version="1.0" encoding="UTF-8"?>
<svg id="Layer_2" data-name="Layer 2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 200">
  <defs>
    <style>
      .cls-1 {
        fill: #00ccbc;
      }

      .cls-1, .cls-2 {
        stroke-width: 0px;
      }

      .cls-2 {
        fill: #fff;
      }
    </style>
  </defs>
  <g id="Layer_1-2" data-name="Layer 1">
    <g>
      <rect class="cls-1" width="200" height="200" rx="15.04" ry="15.04"/>
      <g>
        <g>
          <path class="cls-2" d="M35.8,172.41h5.16l-.86-4v-23.88h-4.94v10.89c-1.49-1.72-3.53-2.73-5.94-2.73-4.94,0-8.76,4.08-8.76,10.07s3.82,10.07,8.76,10.07c2.45,0,4.57-1.05,6.05-2.85l.52,2.43h0Z"/>
          <path class="cls-2" d="M133.42,158.04c1,0,1.93.26,2.78.86l2.34-5.28c-1.08-.67-2.34-.97-3.56-.97-2.23,0-4.08,1.01-5.27,2.88l-.52-2.44h-5.09l.82,3.78v15.53h4.94v-12.31c.67-1.27,1.93-2.06,3.57-2.06h0s0,0,0,0Z"/>
          <polygon class="cls-2" points="87.93 172.41 95.88 172.41 101.04 153.09 95.66 153.09 91.87 168.74 88.08 153.09 82.77 153.09 87.93 172.4 87.93 172.41"/>
          <rect class="cls-2" x="75.2" y="153.09" width="4.94" height="19.31"/>
          <path class="cls-2" d="M53.71,172.76c2.75,0,5.46-.75,7.72-2.21l-1.89-4.27c-1.78.94-3.75,1.5-5.76,1.5-2.6,0-4.42-1.01-5.2-2.88h13.89c.15-.71.22-1.42.22-2.28,0-5.99-4.12-9.99-9.65-9.99s-9.65,4.04-9.65,10.07,4.05,10.07,10.32,10.07h0Z"/>
          <path class="cls-2" d="M179.53,162.75c0-5.99-4.16-10.07-9.77-10.07s-9.77,4.08-9.77,10.07,4.16,10.07,9.76,10.07,9.77-4.08,9.77-10.07h0Z"/>
          <path class="cls-2" d="M112.7,172.82c2.75,0,5.46-.75,7.72-2.21l-1.9-4.27c-1.78.94-3.75,1.5-5.76,1.5-2.6,0-4.42-1.01-5.2-2.88h13.89c.15-.71.22-1.42.22-2.28,0-5.99-4.12-9.99-9.65-9.99s-9.65,4.04-9.65,10.07,4.05,10.07,10.32,10.07h0s0,0,0,0Z"/>
          <path class="cls-2" d="M147.9,172.82c5.61,0,9.76-4.08,9.76-10.07s-4.16-10.07-9.77-10.07-9.77,4.08-9.77,10.07,4.16,10.07,9.76,10.07h0Z"/>
          <polygon class="cls-2" points="65.84 172.4 70.78 172.4 70.78 144.52 65.84 144.52 65.84 172.4 65.84 172.4"/>
          <path class="cls-1" d="M147.9,167.61c-2.86,0-4.97-1.91-4.97-4.87s2.12-4.86,4.97-4.86,4.98,1.87,4.98,4.86-2.08,4.87-4.98,4.87h0Z"/>
          <path class="cls-1" d="M25.26,162.75c0-2.99,2.12-4.86,4.97-4.86s4.98,1.87,4.98,4.86-2.08,4.87-4.97,4.87-4.98-1.91-4.98-4.87Z"/>
          <path class="cls-1" d="M169.77,167.61c-2.86,0-4.97-1.91-4.97-4.87s2.12-4.86,4.97-4.86,4.97,1.87,4.97,4.86-2.08,4.87-4.97,4.87Z"/>
          <path class="cls-1" d="M52.96,157.59c2.56,0,4.23,1.2,4.75,3.41h-9.5c.56-2.21,2.23-3.41,4.75-3.41h0Z"/>
          <path class="cls-1" d="M112.03,157.59c2.56,0,4.23,1.2,4.75,3.41h-9.5c.56-2.21,2.23-3.41,4.75-3.41h0Z"/>
          <path class="cls-2" d="M77.68,150.44c1.74,0,3.08-1.35,3.08-3.14s-1.34-3.14-3.08-3.14-3.12,1.35-3.12,3.14,1.34,3.14,3.12,3.14h0Z"/>
        </g>
        <g>
          <polygon class="cls-2" points="122.96 27.18 117.64 77.6 108.55 35.1 80.06 41.12 89.14 83.62 48.07 92.3 55.32 126.26 127.55 141.52 144.07 104.63 151.93 30.21 122.96 27.18 122.96 27.19 122.96 27.18"/>
          <path class="cls-1" d="M100.14,100.32c-1.49,1.36-3.46,1.23-5.55.54-2.09-.69-3.01-3.2-2.22-6.23.59-2.25,3.36-2.59,4.75-2.61.53,0,1.04.1,1.52.31.98.44,2.64,1.38,2.98,2.82.49,2.07.02,3.81-1.47,5.17h0s0,0,0,0Z"/>
          <path class="cls-1" d="M121.05,102.66c-1.08,1.87-3.92,2.12-6.72.76-1.88-.92-1.87-3.25-1.66-4.68.11-.78.42-1.51.91-2.12.67-.85,1.8-1.95,3.09-1.99,2.11-.06,3.93.89,4.95,2.59,1.03,1.7.52,3.57-.57,5.44h0Z"/>
        </g>
      </g>
    </g>
  </g>
</svg>
```

## File: src/modules/payments/assets/knet-icon.svg
```
<?xml version="1.0" encoding="UTF-8"?>
<svg id="Layer_2" data-name="Layer 2" xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 566.9 566.8">
  <defs>
    <style>
      .cls-1 {
        fill: none;
        stroke: #fff;
        stroke-miterlimit: 10;
        stroke-width: 6px;
      }

      .cls-2 {
        fill: #fff200;
      }

      .cls-2, .cls-3, .cls-4 {
        stroke-width: 0px;
      }

      .cls-3 {
        fill: #fff;
      }

      .cls-4 {
        fill: #00549a;
      }
    </style>
  </defs>
  <g id="Layer_1-2" data-name="Layer 1-2">
    <g>
      <path class="cls-4" d="M34.7,0h497.5c19.2,0,34.7,20.4,34.7,45.6v475.5c0,25.2-15.5,45.6-34.7,45.6H34.7c-19.2,0-34.7-20.4-34.7-45.6V45.6C0,20.4,15.5,0,34.7,0Z"/>
      <rect class="cls-4" x="14.7" y="82.4" width="537.6" height="106.7"/>
      <rect class="cls-4" x="14.7" y="199.5" width="537.6" height="167.8"/>
      <rect class="cls-4" x="14.7" y="377.6" width="537.6" height="106.7"/>
      <g>
        <rect class="cls-3" x="467" y="163.6" width="15.8" height="9.8"/>
        <rect class="cls-3" x="446.8" y="163.6" width="15.8" height="9.8"/>
        <polygon class="cls-3" points="225.3 145.1 215.6 145.1 215.6 131.2 196.1 131.2 196.1 145.1 55.2 145.1 53.5 141.4 66.8 124.1 66.8 111.6 47.6 111.6 26.4 139.2 38.5 165 244.8 165 244.8 131.2 225.3 131.2 225.3 145.1"/>
        <rect class="cls-3" x="227.6" y="113.1" width="15.8" height="9.8"/>
        <rect class="cls-3" x="79.1" y="116.1" width="15.8" height="9.8"/>
        <rect class="cls-3" x="99.7" y="116.1" width="15.8" height="9.8"/>
        <polygon class="cls-3" points="528.3 127.2 470.6 127.2 461.9 119.9 523.1 119.9 516.7 108.8 439.8 108.8 438.6 112.7 465 134.7 510.5 134.7 510.5 140.6 461.4 140.6 444.7 126.7 411.4 126.7 411.4 156.1 356.6 156.1 356.6 144.1 402.8 144.1 402.8 126.7 328 126.7 328 170.4 431.1 170.4 431.1 147.2 442.8 156.9 529.1 156.9 541.2 144.5 541.2 140.4 528.3 127.2"/>
        <rect class="cls-3" x="264" y="136.6" width="36.5" height="15.9"/>
      </g>
      <polygon class="cls-2" points="481.2 350.7 382.5 276.5 479.4 217.1 305.8 217.1 220.8 269.1 220.8 217.1 99.7 217.1 99.7 350.7 220.8 350.7 220.8 281.2 298.5 350.7 481.2 350.7"/>
      <g>
        <path class="cls-3" d="M75.5,470v-66.2h17.4v7.9c2.5-3.2,5.4-5.6,8.8-7.2,3.4-1.6,7.1-2.4,11.3-2.4,7.3,0,12.8,1.9,16.4,5.7,3.6,3.8,5.4,9.5,5.4,17.1v45.1h-17.7v-40c0-4.8-.8-8.1-2.4-10.2-1.6-2-4.2-3-7.8-3s-7.5,1.2-9.9,3.8-3.7,5.9-3.7,10.2v39.3h-17.7,0Z"/>
        <path class="cls-3" d="M294.7,449.1h17.7c-1.8,7-5.4,12.5-10.8,16.4-5.4,4-12,5.9-19.8,5.9s-17.2-3.2-22.8-9.6-8.4-15.1-8.4-26.2,2.8-19.4,8.3-25.6c5.5-6.2,13.1-9.4,22.7-9.4s18,3.1,23.5,9.2c5.5,6.1,8.3,14.9,8.3,26.3s0,2.2,0,2.8c0,.6,0,1.2-.1,1.8h-44.2c.2,5.2,1.5,9.1,3.8,11.8,2.3,2.6,5.6,4,9.9,4s5.5-.6,7.5-1.8c2-1.2,3.5-3,4.6-5.6h0ZM268.9,429.1h26.1c-.2-4.5-1.4-7.9-3.6-10.2-2.2-2.3-5.4-3.5-9.5-3.5s-6.9,1.2-9.1,3.5c-2.2,2.4-3.5,5.8-3.9,10.2h0Z"/>
        <path class="cls-3" d="M489.2,478.2c-1.6,0-3.6.1-5.8.2-2.2.1-3.7.1-4.3.1-6.8,0-11.4-1.3-13.9-3.8s-3.8-7.5-3.8-15v-35.8h-8.8v-12.4h8.8v-18.1h17.5v18.1h10.2v12.4h-10.2v36.7c0,1.8.4,2.9,1.2,3.4s2.4.8,4.8.8h4.3v13.3h0Z"/>
      </g>
      <line class="cls-1" y1="196.3" x2="566.9" y2="196.3"/>
      <line class="cls-1" y1="372.5" x2="566.9" y2="372.5"/>
    </g>
  </g>
</svg>
```

## File: src/modules/payments/assets/pay-cash.svg
```
<?xml version="1.0" encoding="iso-8859-1"?>
<!-- Generator: Adobe Illustrator 19.0.0, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
<svg version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"
     viewBox="0 0 512 512" style="enable-background:new 0 0 512 512;" xml:space="preserve">
<path style="fill:#EAC092;" d="M107.34,372.017v79.287c45.161,1.992,32.13,9.972,110.705,45.301
	c10.008,3.937,33.109,10.385,57.85-0.984c0.013-0.005,0.035-0.015,0.049-0.02l154.365-55.27
	c5.023-2.311,30.361-16.078,20.367-41.717c-11.684-27.341-41.751-15.936-44.271-15.116l-80.589,22.281"/>
<g>
	<path style="fill:#FEDBAB;" d="M198.517,405.188l89.749,28.441c15.663,4.454,31.97-4.633,36.424-20.296l0,0
		c4.454-15.663-4.633-31.97-22.58-38.63l-79.618-27.022c-0.003-0.006-16.999-27.76-57.472-27.76
		c-25.556,0-47.588,20.656-57.679,38.737v36.104"/>
</g>
<path d="M162.75,403.853c-0.65,0-1.31-0.07-1.95-0.2c-0.64-0.12-1.27-0.32-1.88-0.57c-0.6-0.25-1.18-0.56-1.72-0.921
	c-0.55-0.36-1.06-0.78-1.52-1.24s-0.88-0.97-1.24-1.52c-0.37-0.54-0.67-1.12-0.92-1.73c-0.25-0.6-0.45-1.23-0.57-1.87
	c-0.13-0.64-0.2-1.3-0.2-1.95c0-0.65,0.07-1.31,0.2-1.95c0.12-0.64,0.32-1.27,0.57-1.88c0.25-0.6,0.55-1.18,0.92-1.72
	c0.36-0.55,0.78-1.06,1.24-1.52s0.97-0.88,1.52-1.24c0.54-0.36,1.12-0.67,1.72-0.92c0.61-0.25,1.24-0.45,1.88-0.57
	c1.28-0.26,2.61-0.26,3.9,0c0.64,0.12,1.27,0.32,1.87,0.57c0.61,0.25,1.19,0.56,1.73,0.92c0.55,0.36,1.06,0.78,1.52,1.24
	s0.88,0.97,1.24,1.52c0.36,0.54,0.67,1.12,0.92,1.72c0.25,0.61,0.44,1.24,0.57,1.88s0.2,1.3,0.2,1.95c0,0.65-0.07,1.31-0.2,1.95
	c-0.13,0.64-0.32,1.27-0.57,1.87c-0.25,0.61-0.56,1.19-0.92,1.73c-0.36,0.55-0.78,1.06-1.24,1.52s-0.97,0.88-1.52,1.24
	c-0.54,0.36-1.12,0.671-1.73,0.921c-0.6,0.25-1.23,0.45-1.87,0.57C164.06,403.783,163.4,403.853,162.75,403.853z"/>
<rect x="69.46" y="357.379" style="fill:#EAECF0;" width="37.883" height="107.44"/>
<rect x="10" y="357.379" style="fill:#3688C8;" width="59.46" height="126.08"/>
<path d="M459.993,394.982c-0.039-0.1-0.079-0.199-0.121-0.297c-9.204-21.537-30.79-29.497-56.336-20.772l-69.668,19.266
	c-4.028-12.198-14.075-22.578-28.281-27.85c-0.088-0.032-0.176-0.064-0.265-0.094l-76.581-25.992
	c-6.374-8.239-26.34-29.321-63.723-29.321c-26.125,0-49.236,17.922-62.458,37.457H10c-5.523,0-10,4.477-10,10v126.077
	c0,5.523,4.477,10,10,10h59.457c5.523,0,10-4.477,10-10v-8.634h27.883c5.523,0,10-4.477,10-10v-2.878
	c16.254,1.418,21.6,4.501,36.528,13.109c11.48,6.62,28.831,16.625,60.077,30.674c0.145,0.065,0.292,0.127,0.439,0.185
	c5.997,2.359,17.72,6.065,32.173,6.065c10.06,0,21.445-1.797,33.131-7.094l153.991-55.136c0.274-0.098,0.544-0.208,0.808-0.33
	C449.204,442.646,471.135,423.563,459.993,394.982z M59.457,473.455H20V367.378h39.457V473.455z M97.34,454.821H79.457v-87.443
	H97.34V454.821z M426.496,431.074l-153.922,55.111c-0.135,0.048-0.318,0.12-0.451,0.174c-0.135,0.055-0.27,0.113-0.403,0.174
	c-21.437,9.852-41.814,3.954-49.8,0.849c-30.182-13.581-46.291-22.87-58.061-29.657c-16.364-9.436-24.249-13.984-46.519-15.823
	V361.36c9.479-15.536,27.861-31.439,47.679-31.439c33.986,0,48.387,22.105,48.953,22.997c1.221,1.986,3.098,3.483,5.305,4.232
	l79.475,26.974c12.693,4.764,19.401,15.634,16.318,26.474c-1.423,5.006-4.711,9.158-9.257,11.691
	c-4.507,2.511-9.717,3.132-14.683,1.758l-89.593-28.392c-5.268-1.669-10.886,1.247-12.554,6.512
	c-1.669,5.265,1.247,10.885,6.512,12.554l89.749,28.441c0.095,0.03,0.19,0.059,0.286,0.086c3.583,1.019,7.231,1.523,10.857,1.523
	c6.638,0,13.203-1.691,19.161-5.011c9.213-5.133,15.875-13.547,18.759-23.692c0.23-0.81,0.434-1.62,0.611-2.43l75.083-20.8
	c10.844-3.704,25.079-5.039,31.417,9.558C447.978,419.533,430.928,428.96,426.496,431.074z"/>
<polyline style="fill:#26CFAD;" points="239.903,98.841 151.085,10.023 39.729,121.38 230.016,311.667 335.098,206.585 "/>
<path style="fill:#FFD36C;" d="M187.311,114.012L187.311,114.012c0.006-0.02,0.012-0.04,0.017-0.06
	c-10.933,0.747-21.656,5.298-30.014,13.656c-18.356,18.356-18.356,48.116,0,66.472s48.116,18.356,66.472,0
	c8.878-8.878,13.461-20.423,13.752-32.055"/>
<path style="fill:#EAC092;" d="M404.66,155.329V76.042c-45.161-1.992-32.13-9.972-110.705-45.301
	c-10.008-3.937-33.109-10.385-57.85,0.984c-0.013,0.006-0.035,0.015-0.049,0.02L189.483,48.42l48.054,48.054"/>
<g>
	<path style="fill:#00B192;" d="M39.729,121.38l37.752-37.752c20.819,20.819,20.819,54.685,0,75.504L39.729,121.38z"/>
	<path style="fill:#00B192;" d="M192.264,273.915c20.819-20.819,54.685-20.819,75.504,0l-37.752,37.752L192.264,273.915z"/>
	<path style="fill:#00B192;" d="M113.333,47.775l37.752-37.752l37.752,37.752C168.019,68.594,134.152,68.594,113.333,47.775z"/>
	<path style="fill:#00B192;" d="M291.206,182.048c-6.844,18.889-2.706,40.893,12.415,56.014l31.477-31.477"/>
</g>
<g>
	<path style="fill:#FEDBAB;" d="M313.483,122.158l-89.749-28.441c-15.663-4.454-31.97,4.633-36.423,20.296l0,0
		c-4.454,15.663,4.633,31.97,22.58,38.63l79.651,27.033l-0.033-0.011c0,0,16.994,27.76,57.472,27.76
		c25.556,0,47.588-20.656,57.679-38.737v-36.104"/>
</g>
<path d="M349.25,143.493c-0.65,0-1.31-0.07-1.95-0.2c-0.64-0.13-1.27-0.32-1.87-0.57c-0.61-0.25-1.19-0.56-1.73-0.92
	c-0.55-0.36-1.06-0.78-1.52-1.24s-0.88-0.97-1.24-1.52c-0.36-0.54-0.67-1.12-0.92-1.73c-0.25-0.6-0.45-1.23-0.57-1.87
	c-0.13-0.64-0.2-1.3-0.2-1.95s0.07-1.31,0.2-1.95c0.12-0.64,0.32-1.27,0.57-1.88c0.25-0.6,0.56-1.18,0.92-1.72
	c0.36-0.55,0.78-1.06,1.24-1.52s0.97-0.88,1.52-1.24c0.54-0.36,1.12-0.67,1.73-0.92c0.6-0.25,1.23-0.45,1.87-0.57
	c1.29-0.26,2.62-0.26,3.91,0c0.63,0.12,1.26,0.32,1.87,0.57c0.6,0.25,1.18,0.56,1.72,0.92c0.55,0.36,1.06,0.78,1.52,1.24
	s0.88,0.97,1.24,1.52c0.37,0.54,0.67,1.12,0.92,1.72c0.26,0.61,0.45,1.24,0.58,1.88c0.13,0.64,0.19,1.3,0.19,1.95
	s-0.06,1.31-0.19,1.95s-0.32,1.27-0.58,1.87c-0.25,0.61-0.55,1.19-0.92,1.73c-0.36,0.55-0.78,1.06-1.24,1.52s-0.97,0.88-1.52,1.24
	c-0.54,0.36-1.12,0.67-1.72,0.92c-0.61,0.25-1.24,0.44-1.87,0.57C350.56,143.423,349.9,143.493,349.25,143.493z"/>
<rect x="404.66" y="62.529" style="fill:#EAECF0;" width="37.883" height="107.44"/>
<rect x="442.54" y="43.891" style="fill:#3688C8;" width="59.46" height="126.08"/>
<path d="M502,33.891h-59.457c-5.523,0-10,4.477-10,10v8.634H404.66c-5.523,0-10,4.477-10,10v2.878
	c-16.254-1.419-21.6-4.501-36.527-13.109c-11.48-6.62-28.831-16.625-60.078-30.674c-0.145-0.066-0.291-0.127-0.44-0.185
	c-10.171-4.002-36.828-11.876-65.299,1.027l-40.24,14.408L158.157,2.952c-3.905-3.905-10.237-3.905-14.142,0L32.657,114.309
	c-3.602,3.603-4.293,9.85,0,14.143l190.287,190.287c3.045,3.046,10.175,3.967,14.143,0l101.665-101.664
	c2.643,0.228,5.386,0.351,8.229,0.351c26.126,0,49.236-17.922,62.457-37.456H502c5.523,0,10-4.477,10-10V43.891
	C512,38.368,507.523,33.891,502,33.891z M176.449,126.633c1.846,15.362,12.907,29.055,29.964,35.385
	c0.088,0.032,0.176,0.064,0.265,0.094l19.996,6.787c-1.51,6.815-4.927,13.081-9.957,18.112c-14.428,14.426-37.904,14.428-52.33,0
	c-14.428-14.427-14.428-37.902,0-52.33C167.867,131.199,171.974,128.478,176.449,126.633z M196.452,87.586
	c-7.168,3.994-12.792,9.975-16.294,17.211c-11.28,2.089-21.723,7.55-29.915,15.741c-22.225,22.226-22.225,58.389,0.001,80.615
	c11.112,11.112,25.709,16.669,40.307,16.669c14.597,0,29.195-5.556,40.308-16.669c7.23-7.23,12.295-16.116,14.832-25.8
	l33.764,11.459c-3.801,17.608,0.092,36.132,10.593,50.682l-22.837,22.837c-22.098-16.03-52.292-16.03-74.39,0L91.07,158.579
	c7.809-10.74,12.025-23.641,12.025-37.199c0-13.559-4.215-26.459-12.025-37.199l22.817-22.816
	c10.74,7.809,23.64,12.025,37.199,12.025c13.559,0,26.459-4.216,37.199-12.025l21.629,21.629
	C205.247,83.683,200.696,85.221,196.452,87.586z M304.457,223.084c-3.86-6.29-6.044-13.469-6.389-20.796
	c4.79,3.463,10.644,6.856,17.636,9.549L304.457,223.084z M151.085,24.165l22.792,22.792c-6.775,4.19-14.608,6.432-22.792,6.432
	c-8.185,0-16.017-2.241-22.792-6.432L151.085,24.165z M76.663,98.588c4.19,6.775,6.432,14.608,6.432,22.792
	s-2.241,16.017-6.432,22.793L53.871,121.38L76.663,98.588z M230.016,297.525l-22.788-22.788c13.913-8.586,31.661-8.586,45.575,0
	L230.016,297.525z M346.981,197.424c-3.708,0-7.183-0.264-10.432-0.734c-0.013-0.002-0.026-0.004-0.039-0.006
	c-21.596-3.137-33.213-15.411-37.042-20.271c-0.204-0.3-1.073-1.437-1.202-1.626c-1.165-2.082-3.075-3.756-5.511-4.583
	l-79.508-26.985c-12.688-4.762-19.395-15.627-16.321-26.463c0.002-0.007,0.004-0.014,0.006-0.021
	c0.003-0.008,0.005-0.017,0.007-0.025c1.429-4.99,4.711-9.129,9.247-11.656c4.506-2.511,9.715-3.134,14.683-1.757l89.593,28.391
	c5.266,1.671,10.886-1.247,12.554-6.512s-1.247-10.885-6.512-12.554l-71.255-22.58l-0.622-0.622
	c-0.006-0.006-0.012-0.013-0.019-0.019l-36.89-36.89l31.708-11.354c0.107-0.039,0.239-0.088,0.345-0.131
	c0.027-0.011,0.079-0.031,0.105-0.042c0.136-0.055,0.27-0.113,0.403-0.174c21.436-9.852,41.812-3.955,49.799-0.849
	c30.183,13.581,46.293,22.87,58.063,29.657c16.364,9.437,24.249,13.984,46.518,15.823v80.542
	C385.181,181.521,366.799,197.424,346.981,197.424z M414.66,72.525h17.883v87.443H414.66V72.525z M492,159.968h-39.457V53.891H492
	V159.968z"/>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
<g>
</g>
</svg>
```

## File: src/modules/payments/assets/talabat.svg
```
<?xml version="1.0" encoding="UTF-8"?>
<svg id="Layer_2" data-name="Layer 2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 200">
  <defs>
    <style>
      .cls-1 {
        fill: #ff5215;
      }

      .cls-1, .cls-2 {
        stroke-width: 0px;
      }

      .cls-2 {
        fill: #fff;
        fill-rule: evenodd;
      }
    </style>
  </defs>
  <g id="Layer_1-2" data-name="Layer 1">
    <g>
      <rect class="cls-1" width="200" height="200" rx="15.04" ry="15.04"/>
      <path id="Fill-8" class="cls-2" d="M120.78,136.31c-4.27,0-6.99-.78-8.93-3.11-1.55-1.94-2.33-5.05-2.33-9.71v-27.96h19.03l-2.33-20.97h-16.31v-34.56s-7.38.39-9.71.78c-12.43.78-20.58,9.32-20.58,18.64v16.31l-11.65.78v19.42h11.65v32.23c0,9.71,2.72,17.48,7.77,23.3,5.05,5.83,12.82,8.54,22.91,8.54,5.05,0,8.93-.39,12.43-.78h0c5.44-1.17,9.32-5.83,9.32-11.65v-13.98c-3.88,1.55-7.77,2.72-11.26,2.72"/>
    </g>
  </g>
</svg>
```

## File: src/modules/payments/checkout-button.vue
```vue
<template>
  <v-btn
    :variant="selected ? 'outlined' : 'flat'"
    :color="selected ? 'primary' : 'background'"
    class="d-flex px-1 bg-background checkout-btn disabled:opacity-75"
    :class="method.slug"
    height="90"
    id="checkoutBtn"
    :ripple="false"
    :disabled="method.disabled"
  >
    <div class="d-flex flex-column align-center mt-1 btn-content">
      <div>
        <img :src="getIcon(method)" :alt="method.name" width="40" />
      </div>
      <div>
        <p class="mt-2 text-uppercase text-subtitle-2 text-black">
          {{ method.name }}
        </p>
      </div>
    </div>
    <v-icon v-if="selected" class="checkIcon" color="primary"
      >mdi-check-circle</v-icon
    >
  </v-btn>
</template>
⋮----
{{ method.name }}
⋮----
<script setup lang="ts">
import cashSvg from './assets/pay-cash.svg?url';
import cardSvg from './assets/credit.svg?url';
import knetSvg from './assets/knet-icon.svg?url';
import deliverooSvg from './assets/deliveroo.svg?url';
import talabatSvg from './assets/talabat.svg?url';
import type { CachedPaymentMethod } from '@trolley/types';
defineProps<{
  method: CachedPaymentMethod;
  selected: boolean;
}>();
const icons = {
  cash: cashSvg,
  'credit-card': cardSvg,
  manual: knetSvg,
  'k-net': cardSvg,
  'aggregator-deliveroo': deliverooSvg,
  'aggregator-talabat': talabatSvg,
};
function getIcon(paymentMethod: CachedPaymentMethod): string {
  const hasIcon = Boolean(paymentMethod.icon);
  if (hasIcon) return paymentMethod.icon;
  else return icons[paymentMethod.slug] ?? cashSvg;
}
</script>
<style scoped>
.checkout-btn {
  flex-basis: calc(33% - 5px);
  flex-grow: 1;
}
.checkIcon {
  position: absolute;
  right: 5px;
  top: 5px;
  font-size: 1.5rem;
}
.text-subtitle-2 {
  font-size: 0.65rem !important;
}
</style>
```

## File: src/modules/payments/payments-store.ts
```typescript
import { type CachedPaymentMethod, PAYMENT_METHODS } from '@trolley/types';
import { defineStore } from 'pinia';
import { ref, watch } from 'vue';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { trolleyClient } from '@trolley/api-sdk';
import { paymentMethodAdapter } from '@trolley/utils';
import { KNET_CONNECTION_COMMANDS, knetMachineTopic } from '@trolley/knet';
import { subscribe } from '@enegix/events';
import { TRANSACTION_EVENTS } from '@trolley/transactions';
import { EMPLOYEE_REQUESTS } from '../../features/usecases/employee/events';
import { useMediaPrefetch } from '../../composables/prefetchMedia';
import { extractMediaUrlsFromObject } from '../../utils/extractMediaUrls';
⋮----
export const splitPaymentAdapter = (
  paymentMethod: CachedPaymentMethod,
): CachedPaymentMethod => (
⋮----
const fetchPaymentMethods = async () =>
```

## File: src/modules/quick-list/health-check.ts
```typescript
import type { HealthStatus } from '../../features/sync-check/use-health-check';
import { ref } from 'vue';
import { z } from 'zod';
import { itemSchema } from '../../features/items/check';
import { getCachedEntity } from '@trolley/api-sdk';
import { useQuickList } from './store';
⋮----
export const useQuickListCheck = async () =>
```

## File: src/modules/quick-list/store.ts
```typescript
import { defineStore } from 'pinia';
import type { Category, IItem } from '@trolley/types';
import { trolleyClient } from '@trolley/api-sdk';
⋮----
items(): IItem[]
⋮----
fetch()
select(id: number)
```

## File: src/modules/settings/health-check.ts
```typescript
import { computed, ref, watch } from 'vue';
import type { HealthStatus } from '../../features/sync-check/use-health-check';
import { useSettings } from './store';
import { SyncHealthCheck } from '../../../../../libs/api-sdk/src/offline-client/interval-fetch-and-cache';
import { settingsSchema } from '@trolley/types';
export const useSettingsCheck = async () =>
⋮----
const validate = async () =>
```

## File: src/modules/settings/store.ts
```typescript
import { computed, ref, watch } from 'vue';
import { defineStore } from 'pinia';
import { useLocalStorage } from '@vueuse/core';
import { subscribe } from '@enegix/events';
import {
  assignUniqueCodeGeneratorConfig,
  trolleyClient,
} from '@trolley/api-sdk';
import type { ISettings } from '@trolley/types';
import { assignKnetConfig } from '@trolley/knet';
import { extractMediaUrlsFromObject } from '../../utils/extractMediaUrls';
import { useMediaPrefetch } from '../../composables/prefetchMedia';
⋮----
function updateFavicon(href: string)
const fetchSettings = async () =>
```

## File: src/modules/settings/version-update-dialog.vue
```vue
<template>
  <BaseDialog
    :img="UploadImage"
    v-model="showVersionUpdateDialog"
    title="New Version Available"
    text="Please update to the latest version to continue using the application."
    persistent
  >
    <div class="update-progress">
      <div v-if="updateError" class="error-message">
        Update failed: {{ updateError }}
        <v-btn @click="retryUpdate" color="primary" class="mt-2"> Retry </v-btn>
      </div>
      <template v-else>
        <div v-for="step in updateSteps" :key="step.title" class="step">
          <div class="step-icon">
            <template v-if="step.status === 'completed'">✓</template>
            <v-progress-circular
              v-else-if="step.status === 'progress'"
              indeterminate
              size="20"
              width="2"
            />
            <template v-else>◯</template>
          </div>
          <div class="step-title">{{ step.title }}</div>
          <div class="step-status">{{ getStatusText(step.status) }}</div>
        </div>
      </template>
    </div>
    <div class="button-container">
      <v-btn
        v-for="(action, index) in actions"
        :key="index"
        @click="action.handler"
        :disabled="loading || currentStep !== null"
        :loading="action.text === 'Update' && loading"
        class="action-button text-capitalize"
        :color="action.text === 'Later' ? 'weakTextColor' : 'primary'"
        :variant="action.text === 'Later' ? 'outlined' : 'elevated'"
        height="auto"
        :hidden="
          action.text === 'Later' && useSettings()?.settings?.is_strict_version
        "
        density="default"
      >
        {{ actionText(action.text) }}
      </v-btn>
    </div>
  </BaseDialog>
</template>
⋮----
Update failed: {{ updateError }}
⋮----
<template v-else>
        <div v-for="step in updateSteps" :key="step.title" class="step">
          <div class="step-icon">
            <template v-if="step.status === 'completed'">✓</template>
            <v-progress-circular
              v-else-if="step.status === 'progress'"
              indeterminate
              size="20"
              width="2"
            />
            <template v-else>◯</template>
          </div>
          <div class="step-title">{{ step.title }}</div>
          <div class="step-status">{{ getStatusText(step.status) }}</div>
        </div>
      </template>
⋮----
<template v-if="step.status === 'completed'">✓</template>
⋮----
<template v-else>◯</template>
⋮----
<div class="step-title">{{ step.title }}</div>
<div class="step-status">{{ getStatusText(step.status) }}</div>
⋮----
{{ actionText(action.text) }}
⋮----
<script setup lang="ts">
import { onBeforeMount, ref } from 'vue';
import { publish } from '@enegix/events';
import BaseDialog from '../../components/dialogs/base-dialog.vue';
import UploadImage from './update.png';
import {
  currentStep,
  showVersionUpdateDialog,
  updateError,
  updateSteps,
  updateVersion,
} from './version-update';
import { useSettings } from './store';
const loading = ref(false);
onBeforeMount(useSettings().fetchSettings);
const actions = [
  {
    text: 'Later',
    handler: () => {
      showVersionUpdateDialog.value = false;
      publish('UNFREEZE_UI');
    },
  },
  {
    text: 'Update',
    handler: async () => {
      publish('FREEZE_UI');
      loading.value = true;
      updateVersion().finally(() => {
        publish('UNFREEZE_UI');
        loading.value = false;
      });
    },
  },
];
const getStatusText = (status: string) => {
  switch (status) {
    case 'pending':
      return 'Pending';
    case 'progress':
      return 'In progress...';
    case 'completed':
      return 'Completed';
    default:
      return '';
  }
};
const actionText = (text: string) => {
  return updateError.value && text === 'Update' ? 'Retry' : text;
};
const retryUpdate = () => {
  updateError.value = null;
  actions[1].handler();
};
</script>
<style scoped>
.update-progress {
  margin: 1rem 0;
}
.error-message {
  color: #ff4444;
  padding: 1rem;
  background: #ffeeee;
  border-radius: 4px;
  margin-bottom: 1rem;
}
.step {
  display: flex;
  align-items: center;
  padding: 0.5rem 0;
  border-bottom: 1px solid #eee;
}
.step-icon {
  width: 30px;
  margin-right: 1rem;
}
.step-title {
  flex-grow: 1;
  color: rgba(0, 0, 0, 0.87);
}
.step-status {
  color: rgba(0, 0, 0, 0.54);
  margin-left: 1rem;
}
.button-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  max-width: 650px;
  gap: 10px;
  margin-top: 1rem;
}
.action-button {
  flex-grow: 1;
  flex-basis: calc(50% - 10px);
  padding: 10px;
}
</style>
```

## File: src/modules/settings/version-update.ts
```typescript
import { computed, ref, watch } from 'vue';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { whenever } from '@vueuse/core';
import { logicAnd } from '@vueuse/math';
import router from '../../router';
import { toast } from 'vue3-toastify';
import { resolveAfterDelay } from '@trolley/utils';
import { useRegisterSW } from 'virtual:pwa-register/vue';
import { appVersion, latestVersion } from './store';
export interface UpdateStep {
  title: string;
  status: 'pending' | 'progress' | 'completed' | 'error';
}
export enum UpdateSteps {
  UNREGISTERING = 'Unregistering old service workers',
  CLEARING_CACHE = 'Clearing cache',
  REGISTERING = 'Registering new version',
  RELOADING = 'Reloading application',
}
⋮----
export const versionUpdateFeature = async () =>
export const assignNewAppVersion = () =>
export const unregisterServiceWorker = async (
  registrations: Readonly<ServiceWorkerRegistration[]>,
) =>
const injectServiceWorker = async () =>
const handleStep = async (task: () => Promise<void>, step: UpdateSteps) =>
⋮----
export const updateVersion = async () =>
const updateStepStatus = (step: UpdateSteps, status: UpdateStep['status']) =>
export const clearCaches = async () =>
const cleanupRedundantServiceWorkers = async () =>
```

## File: src/pages/cartPage.vue
```vue
<template>
  <categoriesCarousel />
  <cartProducts
    :isClient="false"
    :active-transaction="usePendingTransactionStore()"
  />
  <BottomCards :store="useSaleBottomCards()" />
</template>
<script setup>
import categoriesCarousel from '../components/mainScreen/categoriesCarousel.vue';
import BottomCards from '../components/mainScreen/bottom-cards.vue';
import cartProducts from '../views/cartProducts.vue';
import CartProducts from '../views/cartProducts.vue';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { useSaleBottomCards } from '../store/bottom-cards';
</script>
```

## File: src/pages/clientHomePage.vue
```vue
<template>
  <v-sheet class="bg-background h-100 content-area">
    <headerSection isClient />
    <cartProducts
      isClient
      :active-transaction="activeTransaction"
      :section-title="`${isRefund} Items`"
    />
    <BottomCards
      :store="
        useRefundBottomCards().totalItems > 0
          ? useRefundBottomCards()
          : useSaleBottomCards()
      "
    />
  </v-sheet>
</template>
<script setup lang="ts">
import headerSection from '../components/mainScreen/header-section/headerSection.vue';
import cartProducts from '../views/cartProducts.vue';
import CartProducts from '../views/cartProducts.vue';
import BottomCards from '../components/mainScreen/bottom-cards.vue';
import {
  usePendingTransactionStore,
  useRefundTransactionStore,
} from '@trolley/transactions/vue';
import { computed } from 'vue';
import {
  useRefundBottomCards,
  useSaleBottomCards,
} from '../store/bottom-cards';
const isRefund = computed(() =>
  useRefundTransactionStore().itemsManager.totalItems > 0 ? 'refund' : 'cart',
);
const activeTransaction = computed(() =>
  useRefundTransactionStore().itemsManager.totalItems > 0
    ? useRefundTransactionStore()
    : usePendingTransactionStore(),
);
</script>
```

## File: src/pages/loginPage.vue
```vue
<script lang="ts" setup>
import { login as loginService, startSession } from '../services/auth';
import { toast } from 'vue3-toastify';
import UserSvg from '../assets/icons/Icon awesome-user.svg?url';
import PasswordSvg from '../assets/icons/Icon ionic-ios-key.svg?url';
import { ref } from 'vue';
import router from '../router';
import { useI18n } from 'vue-i18n';
import { goFullscreen, openClientPage } from '../utils/utils';
import { useSettings } from '../modules/settings/store';
const formRef = ref<HTMLFormElement | null>(null);
const valid = ref(false);
const year = new Date().getFullYear();
const formData = ref({
  username: '',
  password: '',
  cash_in: 0,
});
const loading = ref(false);
const step = ref(1);
const requiredRule = [(v) => !!v || 'This field is required'];
const usernameRule = [
  (v) => !!v || 'Username is required',
  (v) => (v && v.length >= 3) || 'Username must be at least 3 characters',
];
function login() {
  if (formRef.value && formRef.value.checkValidity() && loading.value != true) {
    loading.value = true;
    loginService(formData.value.username, formData.value.password)
      .then(() => {
        toast.success('Welcome Back');
        step.value = 2;
      })
      .catch((error) => {
        step.value = 1;
      })
      .finally(() => {
        loading.value = false;
      });
  }
}
function openSession() {
  loading.value = true;
  startSession(formData.value.cash_in)
    .then(() => {
      toast.success('Session Started');
      router.push({ path: '/cart' });
    })
    .finally(() => {
      loading.value = false;
    });
}
const { t, locale } = useI18n();
</script>
<template>
  <v-row class="ma-0" style="height: 100dvh">
    <v-col
      v-if="!$vuetify.display.xlAndUp"
      class="left bg-grey-lighten-4"
      cols="12"
      md="6"
    >
      <img :src="useSettings()?.settings?.login_left" alt="Fingerprint" />
    </v-col>
    <v-col cols="12" md="6">
      <v-row class="h-100">
        <v-col class="text-center" cols="12">
          <img
            :src="useSettings()?.settings?.login_top"
            alt="Logo"
            class="mt-4 w-100 login-top"
          />
        </v-col>
        <v-col class="text-center mt-auto" cols="12">
          <v-form
            ref="formRef"
            v-model="valid"
            @submit.prevent="login"
            v-if="step === 1"
          >
            <v-text-field
              id="username"
              v-model="formData.username"
              :rules="usernameRule"
              class="input mx-auto"
              flat
              label="Username"
              name="username"
              required
              variant="outlined"
            >
              <template #prepend-inner>
                <img :src="UserSvg" alt="username" class="me-2" width="20" />
              </template>
            </v-text-field>
            <v-text-field
              id="password"
              v-model="formData.password"
              :rules="requiredRule"
              class="input mx-auto"
              flat
              label="Password"
              name="password"
              required
              type="password"
              variant="outlined"
            >
              <template #prepend-inner>
                <img :src="PasswordSvg" alt="password" class="me-2" width="20"
              /></template>
            </v-text-field>
            <v-btn
              :loading="loading"
              color="primary"
              height="45"
              size="large"
              type="submit"
              width="455px"
              class="text-uppercase"
              >{{ t('login') }}
            </v-btn>
          </v-form>
          <v-form
            ref="formRef"
            v-model="valid"
            @submit.prevent="openSession"
            v-if="step === 2"
          >
            <v-text-field
              id="cash"
              v-model="formData.cash_in"
              :rules="requiredRule"
              class="input mx-auto"
              flat
              label="Cash In"
              name="cash"
              type="number"
              variant="outlined"
            >
            </v-text-field>
            <v-btn
              :loading="loading"
              color="primary"
              height="45"
              size="large"
              type="submit"
              width="455px"
              class="text-uppercase"
              @click="
                goFullscreen;
                openClientPage;
              "
              >{{ t('confirm') }}
            </v-btn>
          </v-form>
        </v-col>
        <img
          :src="useSettings()?.settings?.login_bottom"
          alt="login selectedProducts group"
          class="mt-auto mx-auto login-bottom"
          width="50%"
        />
        <v-col class="text-center mt-auto" cols="12">
          <footer>
            <div class="w-100 text-center">
              <div class="dashed-hr mx-auto mb-3" />
              <p class="text-weakTextColor">
                ©{{ year }} {{ useSettings()?.settings?.app_name }} - All
                Rights Reserved
              </p>
            </div>
          </footer>
        </v-col>
      </v-row>
    </v-col>
  </v-row>
</template>
⋮----
<template #prepend-inner>
                <img :src="UserSvg" alt="username" class="me-2" width="20" />
              </template>
⋮----
<template #prepend-inner>
                <img :src="PasswordSvg" alt="password" class="me-2" width="20"
              /></template>
⋮----
>{{ t('login') }}
⋮----
>{{ t('confirm') }}
⋮----
©{{ year }} {{ useSettings()?.settings?.app_name }} - All
⋮----
<style scoped>
.left {
  height: 100dvh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.input {
  width: 61%;
}
.login-top {
  max-height: 165px;
}
.login-bottom {
  max-height: 130px;
}
</style>
```

## File: src/pages/notFound.vue
```vue
<template>
  <h1>Terminal ID missing or incorrect</h1>
  <p>Please contact IT to obtain the correct POS link for your terminal.</p>
</template>
<script>
export default {name: 'NotFound'}
</script>
```

## File: src/pages/refundPage.vue
```vue
<script setup lang="ts">
import CartProducts from '../views/cartProducts.vue';
import BottomCards from '../components/mainScreen/bottom-cards.vue';
import { onUnmounted } from 'vue';
import { useRefundTransactionStore } from '@trolley/transactions/vue';
import { useRefundBottomCards } from '../store/bottom-cards';
onUnmounted(useRefundTransactionStore().clear);
</script>
<template>
  <cart-products
    section-title="Refund Items"
    :active-transaction="useRefundTransactionStore()"
  />
  <bottom-cards :store="useRefundBottomCards()" />
</template>
```

## File: src/pages/sessionPage.vue
```vue
<script lang="ts" setup>
import { login as loginService } from '../services/auth';
import AuthSvg from '../assets/images/login/authentication.svg?url';
import { ref } from 'vue';
import router from '../router';
import HeaderSection from '../components/mainScreen/header-section/headerSection.vue';
const formRef = ref<HTMLFormElement | null>(null);
const valid = ref(false);
const year = new Date().getFullYear();
const formData = ref({
  cash_in: 0,
});
const loading = ref(false);
const numberOnlyRule = [
  (v: string) => !!v || 'Cash Starting Balance is required',
  (v: string) => /^[0-9]*$/.test(v) || 'Cash Starting Balance must be a number',
];
function login() {
  if (formRef.value && formRef.value.checkValidity() && loading.value != true) {
    loading.value = true;
    loginService(formData.value.username, formData.value.password)
      .then(() => {
        router.push({ path: '/cart' });
      })
      .finally(() => {
        loading.value = false;
      });
  }
}
</script>
<template>
  <div class="d-flex flex-row align-center h-100">
    <div class="flex-1-1 bg-grey-lighten-4">
      <img :src="AuthSvg" />
    </div>
    <div class="flex-1-1">
      <div class="form-wrapper">
        <header-section :is-client="false" :show-search="false" />
        <v-form ref="formRef" v-model="valid" @submit.prevent="login">
          <v-text-field
            id="username"
            v-model="formData.cash_in"
            :rules="numberOnlyRule"
            class="mx-auto"
            flat
            label="Cash Starting Balance"
            name="cashin"
            required
            variant="outlined"
          >
          </v-text-field>
          <v-btn
            :loading="loading"
            color="primary"
            height="45"
            size="large"
            type="submit"
            block
            >CONFIRM
          </v-btn>
        </v-form>
      </div>
    </div>
  </div>
</template>
<style scoped>
.left {
  height: 100dvh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.input {
  width: 61%;
}
.bg-image {
  background-image: url('../assets/images/trolley_store_interior.jpg');
  background-size: cover;
  background-position: center;
  height: 100vh;
}
.form-wrapper {
  max-width: 80%;
  margin: auto;
}
</style>
```

## File: src/pages/stashedCart.vue
```vue
<script setup lang="ts">
import SectionTitle from '../components/customs/sectionTitle.vue';
import EmptyScreen from '../components/customs/emptyScreen.vue';
import cartImage from '../assets/images/shopping_bucket.jpg';
import moment from 'moment';
import { onMounted } from 'vue';
import { formatPrice } from '@trolley/utils';
import { useI18n } from 'vue-i18n';
import { useStashedTransactionsStore } from '../store/stashed-transactions';
function convertToDateTime(timestamp, format = 'YYYY-MM-DD HH:mm:ss') {
  return moment(timestamp).format(format);
}
const t = useI18n().t;
onMounted(() => {
  useStashedTransactionsStore().clear();
  useStashedTransactionsStore().fetchStashedTransactions();
});
</script>
<template>
  <section-title
    :title="t('stashed') + ' ' + t('cart')"
    icon="mdi mdi-cart-off md-20"
  />
  <empty-screen
    v-if="useStashedTransactionsStore().stashedTransactions.length === 0"
  />
  <div v-else style="height: calc(100dvh - 185px); overflow-y: scroll">
    <div
      v-for="stashedTransaction in useStashedTransactionsStore()
        .stashedTransactions"
      :key="stashedTransaction.id"
    >
      <v-card
        class="d-flex flex-wrap align-center pa-2 mb-2 rounded-lg text-grey-darken-1"
      >
        <v-img
          :src="cartImage"
          class="cart-image mr-2"
          rounded="lg"
          inline
          width="45"
        />
        <div class="flex flex-1-0">
          <p
            class="text-uppercase text-caption font-weight-medium text-grey-lighten-1"
          >
            {{ t('serial') }}
          </p>
          <span class="text-body-2">{{
            convertToDateTime(stashedTransaction.time, 'YYYYMMDDHHmms')
          }}</span>
        </div>
        <div class="flex flex-1-0">
          <p
            class="text-uppercase text-caption font-weight-medium text-grey-lighten-1"
          >
            {{ t('time') }}
          </p>
          <span class="text-body-2">{{
            convertToDateTime(stashedTransaction.time, 'HH:mm A')
          }}</span>
        </div>
        <div class="flex flex-1-0">
          <p
            class="text-uppercase text-caption font-weight-medium text-grey-lighten-1"
          >
            {{ t('items') }}
          </p>
          <span class="text-body-2">{{
            stashedTransaction.itemsManager.totalItems
          }}</span>
        </div>
        <div class="flex flex-1-0">
          <p
            class="text-uppercase text-caption font-weight-medium text-grey-lighten-1"
          >
            {{ t('amount') }}
          </p>
          <span class="text-body-2"
            >{{ formatPrice(stashedTransaction.itemsManager.totalDue) }}
            {{ t('KD') }}</span
          >
        </div>
        <div class="flex flex-1-0 text-right">
          <v-btn
            aria-label="details"
            append-icon="mdi mdi-chevron-right"
            variant="text"
            color="primary"
            size="default"
            @click="
              useStashedTransactionsStore().selectStashedTransaction(
                stashedTransaction.id,
              )
            "
          >
            {{ t('details') }}
          </v-btn>
        </div>
      </v-card>
    </div>
  </div>
</template>
⋮----
{{ t('serial') }}
⋮----
<span class="text-body-2">{{
            convertToDateTime(stashedTransaction.time, 'YYYYMMDDHHmms')
          }}</span>
⋮----
{{ t('time') }}
⋮----
<span class="text-body-2">{{
            convertToDateTime(stashedTransaction.time, 'HH:mm A')
          }}</span>
⋮----
{{ t('items') }}
⋮----
<span class="text-body-2">{{
            stashedTransaction.itemsManager.totalItems
          }}</span>
⋮----
{{ t('amount') }}
⋮----
>{{ formatPrice(stashedTransaction.itemsManager.totalDue) }}
{{ t('KD') }}</span
⋮----
{{ t('details') }}
⋮----
<style scoped></style>
```

## File: src/pages/testPage.vue
```vue
<template>
  <button @click="publish('print')">Print</button>
</template>
<script setup lang="ts">
import { publish } from '@enegix/events';
</script>
```

## File: src/pages/transactionPage.vue
```vue
<script setup lang="ts">
import { isTransactionPaid, isTransactionRefunded, transactions } from '../store/transaction';
import { computed, onMounted } from 'vue';
import { useTransactionStore } from '../store/transaction/state';
import SectionTitle from '../components/customs/sectionTitle.vue';
import { formatPrice } from '../../../../libs/utils/src/lib/formatters';
import type { Transaction } from '@trolley/types';
import { isLocalRecord } from '@trolley/api-sdk';
import { useI18n } from 'vue-i18n';
const headers = [
  { title: 'Date/Time', value: 'dateTime' },
  { title: 'Transaction', value: 'unique_code' },
  { title: 'Items', value: 'items_count' },
  { title: 'Cashier', value: 'cashier_name' },
  { title: 'Amount', value: 'amount' },
  { title: '', value: 'actions', class: 'desktop-only' },
];
const headersToDisplay = computed(() => {
  if (window.innerWidth > 1024) {
    return headers;
  }
  return headers.filter((header) => {
    return header.class !== 'desktop-only';
  });
});
const processedTransactions = computed(() => {
  return transactions().state.transactions.value.map((transaction) => {
    return {
      ...transaction,
      date: new Date(transaction.created_at).toLocaleDateString(),
      time: new Date(transaction.created_at).toLocaleTimeString('en-KW', {
        hour12: false,
        hour: '2-digit',
        minute: '2-digit',
      }),
      initials: getInitials(transaction.cashier_name || 'POS User'),
      cashier_name: transaction.cashier_name || 'POS User',
      amount: formatPrice(transaction.amount || 0) + ' KD',
      items_count: calcItemsCount(transaction)
    };
  });
});
const calcItemsCount = (transaction) => {
  return transaction.items.reduce(
    (acc, item) => acc + (item.is_weighted ? 1 : item.quantity),
    0
  );
};
const getInitials = (name: string): string => {
  const words = name.split(' ');
  let initials = '';
  words.forEach((word) => {
    initials += word.charAt(0);
  });
  return initials;
};
let hasLoadedOnce = false;
const loadTransactions = ({ page, itemsPerPage, sortBy }) => {
  if (!hasLoadedOnce) {
    hasLoadedOnce = true;
  } else {
    transactions().state.pagination.value.current_page = page;
    transactions().state.pagination.value.per_page = itemsPerPage;
    useTransactionStore().loadTransactions();
  }
};
function getTransactionDetails(transactionId: number) {
  transactions().actions.selectTransaction(transactionId);
}
function rowClicked(item, event, index) {
  getTransactionDetails(event.item.id);
}
onMounted(() => {
  transactions().state.singleTransaction.value = null;
  transactions().actions.clearTransactionsFilter(true);
});
function handleColor(item: Transaction) {
  if (isLocalRecord(item)) return 'grey';
  if (isTransactionRefunded(item)) return 'warning';
  if (isTransactionPaid(item)) return 'success';
  return 'red';
}
const { t, locale } = useI18n();
</script>
<style scoped>
.initials {
  min-width: 30px;
  min-height: 30px;
  border-radius: 50%;
}
</style>
<template>
  <section-title
    :title="t('transactions_list').toUpperCase()"
    icon="mdi mdi-list-box-outline md-20"
  />
  <v-data-table-server
    density="default"
    height="calc(100dvh - 230px)"
    :sticky="true"
    :loading="transactions().state.isLoading.value"
    :items-per-page-options="[10, 20, 50, 100]"
    loading-text="Loading transactions..."
    :hover="true"
    :headers="headersToDisplay"
    :items="processedTransactions"
    :items-length="transactions().state.pagination.value.total"
    v-model:items-per-page="transactions().state.pagination.value.per_page"
    @update:options="loadTransactions"
    @click:row="rowClicked"
    style="background-color: white; border-radius: 15px"
  >
    <template v-slot:loading>
      <v-skeleton-loader type="table-row@15"></v-skeleton-loader>
    </template>
    <template v-slot:item.dateTime="{ item }">
      {{ item.date }} {{ item.time }}
    </template>
    <template v-slot:item.unique_code="{ item }">
      <v-badge dot inline :color="handleColor(item)">
        <span class="mr-2">{{ item.unique_code }}</span>
      </v-badge>
    </template>
    <template v-slot:item.cashier_name="{ item }">
      <div class="d-flex align-center">
        <div
          class="d-flex align-center justify-center initials text-primary bg-secondary"
        >
          <p style="font-size: 12px" class="text-uppercase">
            {{ item.initials }}
          </p>
        </div>
        <p class="ms-2 text-capitalize">{{ item.cashier_name }}</p>
      </div>
    </template>
    <template v-slot:item.actions="{ item }">
      <v-btn
        append-icon="mdi mdi-chevron-right"
        variant="text"
        color="primary"
        @click="getTransactionDetails(item.id)"
      >
        Details
      </v-btn>
    </template>
  </v-data-table-server>
</template>
⋮----
<template v-slot:loading>
      <v-skeleton-loader type="table-row@15"></v-skeleton-loader>
    </template>
<template v-slot:item.dateTime="{ item }">
      {{ item.date }} {{ item.time }}
    </template>
⋮----
{{ item.date }} {{ item.time }}
⋮----
<template v-slot:item.unique_code="{ item }">
      <v-badge dot inline :color="handleColor(item)">
        <span class="mr-2">{{ item.unique_code }}</span>
      </v-badge>
    </template>
⋮----
<span class="mr-2">{{ item.unique_code }}</span>
⋮----
<template v-slot:item.cashier_name="{ item }">
      <div class="d-flex align-center">
        <div
          class="d-flex align-center justify-center initials text-primary bg-secondary"
        >
          <p style="font-size: 12px" class="text-uppercase">
            {{ item.initials }}
          </p>
        </div>
        <p class="ms-2 text-capitalize">{{ item.cashier_name }}</p>
      </div>
    </template>
⋮----
{{ item.initials }}
⋮----
<p class="ms-2 text-capitalize">{{ item.cashier_name }}</p>
⋮----
<template v-slot:item.actions="{ item }">
      <v-btn
        append-icon="mdi mdi-chevron-right"
        variant="text"
        color="primary"
        @click="getTransactionDetails(item.id)"
      >
        Details
      </v-btn>
    </template>
```

## File: src/plugins/shared/index.ts
```typescript
import type { PiniaPluginContext } from 'pinia';
import type { Options } from './vanilla';
import { BroadcastChannel as BroadcastChannelImpl } from 'broadcast-channel';
import { serialize } from './utils';
function stateHasKey(
  key: string,
  $state: PiniaPluginContext['store']['$state'],
)
export function PiniaSharedState({
  enable = true,
  initialize = true,
  type,
  serializer,
}: Options &
⋮----
export interface DefineStoreOptionsBase<S, Store> {
    share?: {
      omit?: Array<keyof S>;
      enable?: boolean;
      initialize?: boolean;
      readonlyFromPaths?: string[];
    };
  }
```

## File: src/plugins/shared/utils.ts
```typescript
export interface Serializer {
  serialize: (value: any) => string
  deserialize: (value: string) => any
}
export function serialize(
  obj: Record<string, unknown>,
  serializer: Serializer = { serialize: JSON.stringify, deserialize: JSON.parse },
)
```

## File: src/plugins/shared/vanilla.ts
```typescript
import type { MethodType } from 'broadcast-channel'
import type { Store } from 'pinia'
import type { Serializer } from './utils'
import { BroadcastChannel as BroadcastChannelImpl } from 'broadcast-channel'
import { serialize } from './utils'
export interface Options {
  initialize?: boolean
  type?: MethodType
  serializer?: Serializer
}
export function share<T extends Store, K extends keyof T['$state']>(
  key: K,
  store: T,
  { initialize, serializer, type }: Options,
):
⋮----
const sync = ()
const unshare = () =>
```

## File: src/plugins/axios.js
```javascript
const axiosInstance = axios.create({
```

## File: src/plugins/i18n.js
```javascript
if (!localStorage.getItem("lang")) {
localStorage.setItem("lang", "en");
⋮----
export default createI18n({
⋮----
locale: localStorage.getItem("lang") ? localStorage.getItem("lang") : "en",
```

## File: src/plugins/index.js
```javascript
console.log('ENVIRONMENT:', ENVIRONMENT);
⋮----
export function registerPlugins(app) {
⋮----
.use(i18n)
.use(pinia)
.use(router)
.use(createCustomVuetify())
.use(Vue3Toastify, {
⋮----
.use(VueDragscroll);
⋮----
Sentry.init({
⋮----
beforeSend(event, hint) {
⋮----
const isWhiteListed = whiteListedKeywords.some((keyword) =>
error.message.includes(keyword),
⋮----
const isIgnoredError = ignoredErrors.includes(error.status);
⋮----
browserTracingIntegration({ router }),
replayIntegration({
⋮----
Sentry.setTags({
```

## File: src/plugins/pinia.ts
```typescript
import { createPinia } from 'pinia';
import piniaPluginPersistedstate from 'pinia-plugin-persistedstate';
import { parse, stringify } from 'flatted';
import { PiniaSharedState } from './shared';
```

## File: src/plugins/vuetify.js
```javascript
export default function createCustomVuetify() {
const settingsStore = useSettings();
⋮----
const vuetify = createVuetify({
⋮----
adapter: createVueI18nAdapter({ i18n, useI18n })
⋮----
settingsStore?.$subscribe(() => {
```

## File: src/router/index.js
```javascript
const toVersionedPath = (path) => {
if (path.startsWith(`/${appVersion.value}/`)) return path;
⋮----
const removeOldVersion = (path) => {
return path.replace(/\/v-\d+\//, '/');
⋮----
component: () => import('../layouts/employeeView.vue'),
⋮----
default: () => import('../pages/cartPage.vue'),
aside: () => import('../views/actionPanels/cart/mainCartPanel.vue'),
⋮----
default: () => import('../pages/stashedCart.vue'),
aside: () => import('../views/actionPanels/stashedCartsPanel.vue'),
⋮----
default: () => import('../pages/transactionPage.vue'),
aside: () => import('../views/actionPanels/transactionsPanel.vue'),
⋮----
default: () => import('../pages/refundPage.vue'),
aside: () => import('../views/actionPanels/refundPanel.vue'),
⋮----
default: () =>
⋮----
component: () => import('../layouts/clientView.vue'),
⋮----
default: () => import('../pages/clientHomePage.vue'),
aside: () => import('../views/clientActionPanel.vue'),
⋮----
component: () => import('../layouts/emptyView.vue'),
⋮----
component: () => import('../pages/loginPage.vue'),
⋮----
component: () => import('../pages/testPage.vue'),
⋮----
const router = createRouter({
history: createWebHistory(process.env.BASE_URL),
⋮----
const firstPage = toVersionedPath('/cart');
router.beforeEach(async (to, from, next) => {
⋮----
const token = await getCookie('token');
const sessionStarted = auth().state.sessionStarted;
console.log({
⋮----
const targetVersion = getVersionFromUrl(to.path);
⋮----
const cleanedPath = removeOldVersion(to.path);
const newPath = toVersionedPath(cleanedPath);
⋮----
return next(newPath);
⋮----
next(toVersionedPath('/login'));
} else if (to.path === toVersionedPath('/')) {
next(firstPage);
⋮----
next();
⋮----
console.error('Routing Error:', error);
next(toVersionedPath('/not-found'));
```

## File: src/services/api.ts
```typescript
import { toast } from 'vue3-toastify';
import {
  offlineClientTopic,
  onlineTrolleyClient,
  trolleyClient,
} from '@trolley/api-sdk';
import { TERMINAL_ID, VITE_APP_BASE_URL } from '../env';
import axios, { type AxiosRequestConfig, type AxiosResponse } from 'axios';
import { revokeToken, syncKey } from './auth';
import { getCookie, setCookie } from '../composables/cookies';
import { publish } from '@enegix/events';
⋮----
export const injectSDKConfig = () =>
⋮----
async function errorHandler(response: AxiosResponse)
⋮----
// validation error, show toast with array of errors
⋮----
async function successHandler(response: AxiosResponse)
async function attachHeaders(request: AxiosRequestConfig)
export const injectAccessToken = async (token: string) =>
const assignTokenToSDK = (token: string) =>
```

## File: src/services/auth.ts
```typescript
import { injectAccessToken } from './api';
import { auth, type Auth } from '../modules/auth';
import { removeCookie } from '../composables/cookies';
import { publish } from '@enegix/events';
import { AUTH_EVENTS } from '../modules/auth/events';
import router from '../router';
import { VITE_POS_SYNC_KEY } from '../env';
import { generateSyncKey, trolleyClient } from '@trolley/api-sdk';
async function login(username, password)
async function startSession(cash_in = 0)
async function checkOrNot()
async function logout(cash_out = 0, end_knet = 0, type = 1)
async function revokeToken()
```

## File: src/services/navigator.ts
```typescript
import router from '../router/index';
export class Navigator
⋮----
goTo(path: string): Promise<void | Error>
goToHome(): Promise<void | Error>
goToCart(): Promise<void | Error>
```

## File: src/store/coupons/index.ts
```typescript
import { useCoupons } from './state';
import { storeToRefs } from 'pinia';
export const coupons = () => (
```

## File: src/store/coupons/state.ts
```typescript
import { nextTick, ref, watch } from 'vue';
import { defineStore } from 'pinia';
import { subscribe } from '@enegix/events';
import { TRANSACTION_EVENTS } from '@trolley/transactions';
import { trolleyClient } from '@trolley/api-sdk';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import {
  CART_ACTIONS,
  EMPLOYEE_REQUESTS,
} from '../../features/usecases/employee/events';
import { CART_TAB, COUPON_TAB, globalStore } from '../global';
import type { ICoupon } from '@trolley/types';
import { useCustomer } from '../customer/state';
import { useSaleBottomCards } from '../bottom-cards';
import { AUTH_EVENTS } from '../../modules/auth/events';
⋮----
const applyCoupon = async (coupon: ICoupon, employee_id?: string) =>
function unSelectCoupon()
const fetchCoupons = async () =>
```

## File: src/store/customer/actions.ts
```typescript
import type { Customer } from './types';
import { trolleyClient } from '@trolley/api-sdk';
import { useCustomer } from './state';
import { validatePhone } from '@trolley/utils';
export const fetchCustomerDetails = async (
```

## File: src/store/customer/state.ts
```typescript
import { defineStore } from 'pinia';
import { computed, ref, watch } from 'vue';
import type { Customer } from './types';
import { subscribe } from '@enegix/events';
import { EMPLOYEE_REQUESTS } from '../../features/usecases/employee/events';
import { AUTH_EVENTS } from '../../modules/auth/events';
import { RECEIPT_PRINTED } from '../../features/printing/events';
import { TRANSACTION_EVENTS } from '@trolley/transactions';
import { useLoyaltyStore } from '../../modules/loyalty/store/loyalty-store';
⋮----
const resetCustomer = () =>
const resetReceiptCustomer = () =>
```

## File: src/store/customer/types.ts
```typescript
import type { ICoupon } from '@trolley/types';
export interface Customer {
  id: number;
  name: string;
  phone: string;
  employee_ID: string | null;
  loyalty: Loyalty;
  discounts: ICoupon[];
}
export interface Loyalty {
  pointsBalance: number;
  pointsValue: number;
  redeem_factor: number;
  earn_factor: number;
}
```

## File: src/store/transaction/actions.ts
```typescript
import {useTransactionStore} from "./state";
import moment from "moment";
const selectTransaction = (transactionId: number) =>
const clearTransactionsFilter = (reset= false) =>
```

## File: src/store/transaction/index.ts
```typescript
import { storeToRefs } from 'pinia';
import { useTransactionStore } from './state';
import { transactionActions } from './actions';
import {
  type Transaction,
  TRANSACTION_STATUS,
  TRANSACTION_TYPE,
} from '@trolley/types';
⋮----
export const transactions = () => (
export const isTransactionPaid = (transaction: Transaction) =>
export const isTransactionRefunded = (transaction: Transaction) =>
```

## File: src/store/transaction/state.ts
```typescript
import { defineStore } from 'pinia';
import type { Pagination, PaymentMethods, TransactionFilter } from './types';
import { ref } from 'vue';
import { trolleyClient } from '@trolley/api-sdk';
import moment from 'moment';
import type { Transaction } from '@trolley/types';
⋮----
function getCleanParameters(params)
function resetFilters()
function resetAndReload()
function loadTransactions()
```

## File: src/store/transaction/types.ts
```typescript
export interface Pagination {
  current_page: number;
  last_page: number;
  total: number;
  per_page: number;
}
export interface TransactionFilter {
  id: number | null;
  minAmount: number | null;
  maxAmount: number | null;
  fromDate: string | null;
  toDate: string | null;
  transactionId: string | null;
  paymentMethodId: number | null;
  uniqueCode: string | null;
}
export interface PaymentMethods {
  title: string;
  value: number;
}
```

## File: src/store/app-machine.ts
```typescript
import { createMachine } from 'xstate';
import { defineStore } from 'pinia';
import { subscribe } from '@enegix/events';
```

## File: src/store/bottom-cards.ts
```typescript
import { defineStore } from 'pinia';
import { formatPrice } from '@trolley/utils';
import {
  usePendingTransactionStore,
  useRefundTransactionStore,
} from '@trolley/transactions/vue';
import { computed, ref } from 'vue';
```

## File: src/store/clientScreen.ts
```typescript
import { defineStore } from 'pinia';
⋮----
state()
```

## File: src/store/global.ts
```typescript
import { reactive, watch } from 'vue';
import { subscribe } from '@enegix/events';
import { TRANSACTION_EVENTS } from '@trolley/transactions';
import { BackendStatusTopic } from '../features/app-mode/backend-status-topic';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { usePaymentMethods } from '../modules/payments/payments-store';
import { AUTH_EVENTS } from '../modules/auth/events';
```

## File: src/store/stashed-transactions.ts
```typescript
import { defineStore } from 'pinia';
import { StashedTransaction } from '@trolley/transactions';
⋮----
selectStashedTransaction(stashId: number)
fetchStashedTransactions()
clear()
```

## File: src/store/uiUpdate.ts
```typescript

```

## File: src/utils/debouncer.ts
```typescript
import { debounce } from 'vue-debounce';
export const debouncer = (
  callback: (props: any) => void | Promise<void>,
  delay = 800,
)
```

## File: src/utils/extractMediaUrls.ts
```typescript
export function extractMediaUrlsFromObject(obj: unknown): string[]
⋮----
const searchForMediaUrls = (value: any) =>
```

## File: src/utils/path.ts
```typescript

```

## File: src/utils/runAfterStoreHydrated.ts
```typescript
import { nextTick } from 'vue';
export function runAfterStoreHydrated(cb: () => void)
```

## File: src/utils/sync.ts
```typescript
export const removeAllSyncHealthChecks = () =>
```

## File: src/utils/utils.spec.ts
```typescript
import { describe, expect, test } from 'vitest';
import { getVersionFromUrl } from './utils';
```

## File: src/utils/utils.ts
```typescript
export function getVersionFromUrl(url: string): string
export function openClientPage()
export function goFullscreen()
```

## File: src/views/actionPanels/cart/checkoutView.vue
```vue
<script setup lang="ts">
import customCard from '../../../components/customs/customCard.vue';
import { CHECKOUT_TAB, globalStore } from '../../../store/global';
import walletSvg from '../../../assets/icons/wallet.svg?url';
import CheckoutButton from '../../../modules/payments/checkout-button.vue';
import { useI18n } from 'vue-i18n';
import {
  almostEqualOrMore,
  formatPrice,
  toFloat,
  validateIntegerInput,
} from '@trolley/utils';
import { computed, onMounted, onUnmounted, ref, watch } from 'vue';
import { publish, subscribe } from '@enegix/events';
import { isCashPaymentMethod } from '@trolley/knet';
import SplitPayments from '../../../components/split-payments.vue';
import { calcCash } from '../../../features/printing/helpers';
import { TRANSACTION_EVENTS } from '@trolley/transactions';
import { scannerTopic } from '../../../features/usecases/scanner/events';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { LAST_COMMIT_HASH } from '../../../env';
import { type CachedPaymentMethod, PAYMENT_METHODS } from '@trolley/types';
import { useCustomer } from '../../../store/customer/state';
import { usePaymentMethods } from '../../../modules/payments/payments-store';
import AppliedCoupons from '../../../components/appliedCoupons.vue';
import { useCoupons } from '../../../store/coupons/state';
const loading = computed(() => usePendingTransactionStore().isSubmitting);
const totalDue = computed(
  () => usePendingTransactionStore().itemsManager.totalDue,
);
const paymentOptions = computed(() => usePaymentMethods().paymentMethods);
const selectedPayment = ref<CachedPaymentMethod | null>(null);
const t = useI18n().t;
const amount = ref('');
const code = ref('');
const otherMethods = computed(() => {
  return (
    usePendingTransactionStore().paymentsManager.totalPaidAmount -
    calcCash(usePendingTransactionStore().paymentsManager.payments)
  );
});
const cashChangeValue = computed(() => {
  if (usePaymentMethods().isSplitMode) {
    return formatPrice(
      Number(amount.value) - totalDue.value + otherMethods.value,
    );
  } else {
    return formatPrice(Number(amount.value) - totalDue.value);
  }
});
const resetValues = () => {
  amount.value = '';
  code.value = '';
};
watch([() => globalStore.tab, () => usePaymentMethods().isSplitMode], () => {
  resetValues();
  selectedPayment.value = null;
});
watch(
  () => selectedPayment.value,
  () => {
    if (usePaymentMethods().isSplitMode) {
      return;
    }
    resetValues();
  },
);
// watch(() => selectedPayment.value, resetValues);
onUnmounted(resetValues);
subscribe([TRANSACTION_EVENTS.CREATING], resetValues);
function validateCash(amount: any) {
  // Early return if cash is not required
  if (!selectedPayment?.value?.requires_cash) return true;
  // Validate if amount is a valid number
  const isNumber = /^\d*\.?\d*$/.test(amount);
  if (!isNumber) return false;
  const isSplit = usePaymentMethods().isSplitMode;
  const isRepeatable = selectedPayment.value.repeatable;
  const remainingAmount = usePendingTransactionStore().remainingAmount;
  const sumPayments = usePendingTransactionStore().paymentsManager.sumPayments(
    selectedPayment.value.id,
  );
  // Handle split mode payments
  if (isSplit) {
    if (isRepeatable) {
      return almostEqualOrMore(remainingAmount, amount);
    } else {
      return almostEqualOrMore(remainingAmount + sumPayments, amount);
    }
  }
  // Handle non-split payments
  return almostEqualOrMore(amount, remainingAmount);
}
const validateRequiresCode = (code: any) => {
  if (selectedPayment.value?.payment_method_id === PAYMENT_METHODS.MANUAL_KNET)
    return String(code).length >= 3;
  else if (selectedPayment.value?.is_numeric) {
    return validateIntegerInput(code);
  }
  return !!code;
};
async function checkout() {
  if (!selectedPayment.value) return;
  const isNotSplit = !usePaymentMethods().isSplitMode;
  if (isNotSplit) {
    const isCash = isCashPaymentMethod(selectedPayment.value.id);
    usePendingTransactionStore().paymentsManager.addPayment({
      amount: usePendingTransactionStore().itemsManager.totalDue,
      extra: isCash ? Number(amount.value) : code.value,
      ...selectedPayment.value,
    });
  }
  usePendingTransactionStore().submit({
    commit_hash: LAST_COMMIT_HASH,
    phone: useCustomer().customerPhone,
    customer_id: useCustomer()?.customer?.id,
    rate: useCustomer()?.rating,
  });
}
onMounted(() => {
  subscribe(TRANSACTION_EVENTS.PAID, () => {
    back();
  });
  scannerTopic.subscribe('SCANNED_RECEIPT', (data) => {
    if (selectedPayment.value?.requires_code) {
      code.value = data;
    }
  });
  watch(
    [() => globalStore.tab, () => useCustomer().customer],
    ([newTab, newCustomer]) => {
      const isCheckOutTab = newTab === CHECKOUT_TAB;
      const noSelectedCoupon = !useCoupons().selectedCoupon;
      if (isCheckOutTab && newCustomer?.employee_ID && noSelectedCoupon) {
        const { employeeDiscount, applyCoupon } = useCoupons();
        if (employeeDiscount) {
          applyCoupon(employeeDiscount, newCustomer.employee_ID);
        }
      }
    },
    { immediate: true },
  );
});
function back() {
  globalStore.tab = 'main';
  publish('checkout-back');
}
const handleSelectPayment = (btn) => {
  selectedPayment.value = btn;
  if (
    usePendingTransactionStore().remainingAmount > 0 &&
    usePaymentMethods().isSplitMode &&
    totalDue.value != usePendingTransactionStore().remainingAmount
  ) {
    if (btn.repeatable) {
      amount.value = usePendingTransactionStore().remainingAmount.toString();
    } else {
      amount.value = (
        usePendingTransactionStore().remainingAmount +
        usePendingTransactionStore().paymentsManager.sumPayments(btn.id)
      ).toString();
    }
  }
};
</script>
<template>
  <div class="d-flex flex-column justify-space-between">
    <div>
      <applied-coupons />
      <div v-dragscroll class="payment-options-wrapper no-text-highlight">
        <customCard
          title="payment_method"
          height="300"
          class="mt-3 overflow-y-scroll"
        >
          <template #actions>
            <v-switch
              class="switcher"
              color="primary"
              :disabled="
                almostEqualOrMore(0, totalDue) || usePaymentMethods().isLoading
              "
              v-model="usePaymentMethods().isSplitMode"
              label="Split"
              hide-details
            />
          </template>
          <template #icon>
            <img :src="walletSvg" alt="payment" />
          </template>
          <template #body>
            <div
              class="w-100 d-flex flex-wrap align-center justify-space-between ga-2"
            >
              <v-skeleton-loader
                v-if="paymentOptions.length === 0"
                class="d-flex flex-row checkout-btn"
                height="90"
                width="100%"
                :ripple="false"
                type="card"
              >
              </v-skeleton-loader>
              <checkout-button
                v-for="(btn, index) in paymentOptions"
                :key="index"
                :method="btn"
                :selected="selectedPayment === btn"
                @click="handleSelectPayment(btn)"
                :style="
                  usePendingTransactionStore().isSubmitting
                    ? 'opacity: 0.5'
                    : ''
                "
              />
            </div>
            <div class="d-flex flex-column mt-8 ga-2">
              <v-text-field
                aria-label="Code"
                v-if="selectedPayment?.requires_code"
                autofocus
                type="tel"
                class="textField no-spinner"
                variant="outlined"
                color="background"
                :label="selectedPayment.inputName + ` ID`"
                :rules="[
                  (v) =>
                    validateRequiresCode(v) ||
                    t(`payment_input_error`, {
                      paymentName: `${selectedPayment?.inputName}  ID`,
                    }),
                ]"
                validate-on="input"
                v-model="code"
                :readonly="selectedPayment.is_scanned"
                :hint="selectedPayment.is_scanned ? 'Scan the code' : ''"
                :persistent-hint="selectedPayment.is_scanned"
              />
              <v-text-field
                aria-label="Amount"
                v-if="selectedPayment?.requires_cash"
                autofocus
                class="textField"
                variant="outlined"
                color="background"
                :label="t('Amount')"
                :rules="[(v) => validateCash(v) || t('amount_error')]"
                validate-on="input"
                v-model="amount"
              >
                <template
                  v-slot:append-inner
                  v-if="usePaymentMethods().isSplitMode"
                >
                  <v-btn
                    aria-label="AddOrEditSplitPayment"
                    color="primary"
                    :disabled="
                      isNaN(Number(amount)) ||
                      almostEqualOrMore(0, Number(amount)) ||
                      (selectedPayment?.requires_code &&
                        !validateRequiresCode(code)) ||
                      (selectedPayment?.requires_cash && !validateCash(amount))
                    "
                    @click="
                      usePendingTransactionStore().paymentsManager.addPayment({
                        amount: Number(amount),
                        extra: isCashPaymentMethod(selectedPayment.id)
                          ? Number(amount)
                          : Number(code),
                        ...selectedPayment,
                      });
                      resetValues();
                    "
                  >
                    <span
                      v-if="
                        !selectedPayment.repeatable &&
                        usePendingTransactionStore().paymentsManager.hasPayment(
                          selectedPayment.id,
                        )
                      "
                    >
                      EDIT
                    </span>
                    <span v-else>ADD</span>
                  </v-btn>
                </template>
              </v-text-field>
            </div>
            <v-sheet
              v-if="
                selectedPayment?.slug === 'cash' &&
                validateCash(amount) &&
                toFloat(cashChangeValue) > 0
              "
              height="50"
              class="d-flex flex-row justify-space-between text-overline px-2"
            >
              <span>{{ t('change') }}</span>
              <span>{{ formatPrice(cashChangeValue) }}</span>
            </v-sheet>
          </template>
        </customCard>
        <split-payments
          class="mt-4"
          v-if="
            usePaymentMethods().isSplitMode &&
            usePendingTransactionStore().paymentsManager.payments.length > 0
          "
        />
      </div>
    </div>
    <div class="d-flex mt-auto">
      <v-btn
        color="weakTextColor"
        variant="outlined"
        width="20%"
        :icon="
          useI18n().locale.value == 'en'
            ? 'mdi mdi-arrow-left'
            : 'mdi mdi-arrow-right'
        "
        @click="back()"
      >
      </v-btn>
      <v-btn
        :disabled="
          // single mode
          (!usePaymentMethods().isSplitMode &&
            ((selectedPayment?.requires_cash && !validateCash(amount)) ||
              (selectedPayment?.requires_code &&
                !validateRequiresCode(code)))) ||
          !selectedPayment ||
          // split
          (usePaymentMethods().isSplitMode &&
            !usePendingTransactionStore().isSubmittable) ||
          loading ||
          useCoupons().isApplyingCoupon
        "
        @click="checkout"
        :loading="loading"
        color="primary"
        class="ms-3 text-uppercase"
        width="75%"
        size="large"
      >
        {{ t('complete_order') }}
      </v-btn>
    </div>
  </div>
</template>
⋮----
<template #actions>
            <v-switch
              class="switcher"
              color="primary"
              :disabled="
                almostEqualOrMore(0, totalDue) || usePaymentMethods().isLoading
              "
              v-model="usePaymentMethods().isSplitMode"
              label="Split"
              hide-details
            />
          </template>
<template #icon>
            <img :src="walletSvg" alt="payment" />
          </template>
<template #body>
            <div
              class="w-100 d-flex flex-wrap align-center justify-space-between ga-2"
            >
              <v-skeleton-loader
                v-if="paymentOptions.length === 0"
                class="d-flex flex-row checkout-btn"
                height="90"
                width="100%"
                :ripple="false"
                type="card"
              >
              </v-skeleton-loader>
              <checkout-button
                v-for="(btn, index) in paymentOptions"
                :key="index"
                :method="btn"
                :selected="selectedPayment === btn"
                @click="handleSelectPayment(btn)"
                :style="
                  usePendingTransactionStore().isSubmitting
                    ? 'opacity: 0.5'
                    : ''
                "
              />
            </div>
            <div class="d-flex flex-column mt-8 ga-2">
              <v-text-field
                aria-label="Code"
                v-if="selectedPayment?.requires_code"
                autofocus
                type="tel"
                class="textField no-spinner"
                variant="outlined"
                color="background"
                :label="selectedPayment.inputName + ` ID`"
                :rules="[
                  (v) =>
                    validateRequiresCode(v) ||
                    t(`payment_input_error`, {
                      paymentName: `${selectedPayment?.inputName}  ID`,
                    }),
                ]"
                validate-on="input"
                v-model="code"
                :readonly="selectedPayment.is_scanned"
                :hint="selectedPayment.is_scanned ? 'Scan the code' : ''"
                :persistent-hint="selectedPayment.is_scanned"
              />
              <v-text-field
                aria-label="Amount"
                v-if="selectedPayment?.requires_cash"
                autofocus
                class="textField"
                variant="outlined"
                color="background"
                :label="t('Amount')"
                :rules="[(v) => validateCash(v) || t('amount_error')]"
                validate-on="input"
                v-model="amount"
              >
                <template
                  v-slot:append-inner
                  v-if="usePaymentMethods().isSplitMode"
                >
                  <v-btn
                    aria-label="AddOrEditSplitPayment"
                    color="primary"
                    :disabled="
                      isNaN(Number(amount)) ||
                      almostEqualOrMore(0, Number(amount)) ||
                      (selectedPayment?.requires_code &&
                        !validateRequiresCode(code)) ||
                      (selectedPayment?.requires_cash && !validateCash(amount))
                    "
                    @click="
                      usePendingTransactionStore().paymentsManager.addPayment({
                        amount: Number(amount),
                        extra: isCashPaymentMethod(selectedPayment.id)
                          ? Number(amount)
                          : Number(code),
                        ...selectedPayment,
                      });
                      resetValues();
                    "
                  >
                    <span
                      v-if="
                        !selectedPayment.repeatable &&
                        usePendingTransactionStore().paymentsManager.hasPayment(
                          selectedPayment.id,
                        )
                      "
                    >
                      EDIT
                    </span>
                    <span v-else>ADD</span>
                  </v-btn>
                </template>
              </v-text-field>
            </div>
            <v-sheet
              v-if="
                selectedPayment?.slug === 'cash' &&
                validateCash(amount) &&
                toFloat(cashChangeValue) > 0
              "
              height="50"
              class="d-flex flex-row justify-space-between text-overline px-2"
            >
              <span>{{ t('change') }}</span>
              <span>{{ formatPrice(cashChangeValue) }}</span>
            </v-sheet>
          </template>
⋮----
<template
                  v-slot:append-inner
                  v-if="usePaymentMethods().isSplitMode"
                >
                  <v-btn
                    aria-label="AddOrEditSplitPayment"
                    color="primary"
                    :disabled="
                      isNaN(Number(amount)) ||
                      almostEqualOrMore(0, Number(amount)) ||
                      (selectedPayment?.requires_code &&
                        !validateRequiresCode(code)) ||
                      (selectedPayment?.requires_cash && !validateCash(amount))
                    "
                    @click="
                      usePendingTransactionStore().paymentsManager.addPayment({
                        amount: Number(amount),
                        extra: isCashPaymentMethod(selectedPayment.id)
                          ? Number(amount)
                          : Number(code),
                        ...selectedPayment,
                      });
                      resetValues();
                    "
                  >
                    <span
                      v-if="
                        !selectedPayment.repeatable &&
                        usePendingTransactionStore().paymentsManager.hasPayment(
                          selectedPayment.id,
                        )
                      "
                    >
                      EDIT
                    </span>
                    <span v-else>ADD</span>
                  </v-btn>
                </template>
⋮----
<span>{{ t('change') }}</span>
<span>{{ formatPrice(cashChangeValue) }}</span>
⋮----
{{ t('complete_order') }}
⋮----
<style scoped>
.payment-options-wrapper {
  height: calc(100vh - 215px);
  overflow-y: scroll;
}
.overflow-y-scroll {
  overflow-y: scroll;
}
.switcher {
  text-transform: uppercase;
  font-size: 15px;
  font-weight: 500;
  color: #333333;
}
</style>
```

## File: src/views/actionPanels/cart/couponsView.vue
```vue
<template>
  <div style="height: 100dvh">
    <v-tabs
      bg-color="background"
      slider-color="transparent"
      selected-class="text-primary bg-white font-weight-bold"
      style="border-radius: 10px; padding: 5px; box-sizing: unset"
      fixed-tabs
      v-model="tab"
    >
      <v-tab
        value="general"
        prepend-icon="mdi mdi-ticket-percent-outline"
        class="text-uppercase"
        :ripple="!!useLoyaltyStore()?.is_loyalty_enabled"
        :style="
          !useLoyaltyStore()?.is_loyalty_enabled
            ? 'flex: 1 1 100%; max-width: 100% ; cursor: default'
            : ''
        "
      >
        {{ t('general') }}
      </v-tab>
      <v-tab
        v-if="useLoyaltyStore()?.is_loyalty_enabled"
        :disabled="!hasCustomer"
        value="customer"
        prepend-icon="mdi mdi-account-outline"
        class="text-uppercase"
      >
        {{ t('Customer') }}
      </v-tab>
    </v-tabs>
    <v-window v-model="tab" class="tab">
      <v-window-item value="general">
        <div
          v-dragscroll
          class="d-flex flex-column align-content-start bg-grey-lighten-3x rounded-lg mt-2 coupons-wrapper no-text-highlight"
        >
          <new-coupon
            v-for="(coupon, index) in generalCoupons.value"
            :key="index"
            :coupon="coupon"
          />
        </div>
      </v-window-item>
      <v-window-item value="customer">
        <div
          v-dragscroll
          class="d-flex flex-column align-content-start bg-grey-lighten-3x rounded-lg mt-2 coupons-wrapper no-text-highlight"
        >
          <new-coupon
            v-for="(coupon, index) in customerCoupons"
            :key="index"
            :coupon="coupon"
          />
        </div>
      </v-window-item>
    </v-window>
    <div id="applied_coupons">
      <customCard title="applied_coupons" :img="true">
        <template #icon>
          <img :src="VourcherSvg" alt="loyalty card" width="20" />
        </template>
        <template #body>
          <div v-if="!selectedCoupon">
            <v-text-field
              prepend-inner-icon="mdi mdi-barcode"
              label="Enter Coupon Code"
              flat
              hide-details
              class="border rounded h-4"
              v-model="manualCoupon"
              v-on:keyup.enter="applyManualCoupon"
            >
              <template #append-inner>
                <v-btn
                  aria-label="AddCoupon"
                  color="primary"
                  :disabled="!manualCoupon || useCoupons().isApplyingCoupon"
                  @click="applyManualCoupon"
                  :loading="isLoading"
                >
                  <span>ADD</span>
                </v-btn>
              </template>
            </v-text-field>
          </div>
          <div v-else>
            <v-card
              class="mx-auto pl-2 mb-2"
              color="grey-lighten-3"
              variant="elevated"
              prepend-icon="mdi-gift-outline"
              :coupon="selectedCoupon"
              :subtitle="
                '[' +
                selectedCoupon.code +
                '] => ' +
                selectedCoupon.value +
                (selectedCoupon.type === 0 ? '%' : t('KD'))
              "
              :key="selectedCoupon.code"
            >
              <template #append>
                <v-btn
                  icon="mdi-trash-can-outline"
                  color="error"
                  variant="plain"
                  @click="useCoupons().unSelectCoupon"
                />
              </template>
            </v-card>
          </div>
        </template>
      </customCard>
    </div>
    <div class="d-flex mt-auto">
      <v-btn
        block
        color="primary"
        class="text-uppercase"
        size="large"
        @click="globalStore.tab = 'checkout'"
      >
        Confirm
      </v-btn>
    </div>
  </div>
</template>
⋮----
{{ t('general') }}
⋮----
{{ t('Customer') }}
⋮----
<template #icon>
          <img :src="VourcherSvg" alt="loyalty card" width="20" />
        </template>
<template #body>
          <div v-if="!selectedCoupon">
            <v-text-field
              prepend-inner-icon="mdi mdi-barcode"
              label="Enter Coupon Code"
              flat
              hide-details
              class="border rounded h-4"
              v-model="manualCoupon"
              v-on:keyup.enter="applyManualCoupon"
            >
              <template #append-inner>
                <v-btn
                  aria-label="AddCoupon"
                  color="primary"
                  :disabled="!manualCoupon || useCoupons().isApplyingCoupon"
                  @click="applyManualCoupon"
                  :loading="isLoading"
                >
                  <span>ADD</span>
                </v-btn>
              </template>
            </v-text-field>
          </div>
          <div v-else>
            <v-card
              class="mx-auto pl-2 mb-2"
              color="grey-lighten-3"
              variant="elevated"
              prepend-icon="mdi-gift-outline"
              :coupon="selectedCoupon"
              :subtitle="
                '[' +
                selectedCoupon.code +
                '] => ' +
                selectedCoupon.value +
                (selectedCoupon.type === 0 ? '%' : t('KD'))
              "
              :key="selectedCoupon.code"
            >
              <template #append>
                <v-btn
                  icon="mdi-trash-can-outline"
                  color="error"
                  variant="plain"
                  @click="useCoupons().unSelectCoupon"
                />
              </template>
            </v-card>
          </div>
        </template>
⋮----
<template #append-inner>
                <v-btn
                  aria-label="AddCoupon"
                  color="primary"
                  :disabled="!manualCoupon || useCoupons().isApplyingCoupon"
                  @click="applyManualCoupon"
                  :loading="isLoading"
                >
                  <span>ADD</span>
                </v-btn>
              </template>
⋮----
<template #append>
                <v-btn
                  icon="mdi-trash-can-outline"
                  color="error"
                  variant="plain"
                  @click="useCoupons().unSelectCoupon"
                />
              </template>
⋮----
<script setup lang="ts">
import customCard from '../../../components/customs/customCard.vue';
import { globalStore } from '../../../store/global';
import VourcherSvg from '../../../assets/icons/voucher.svg?url';
import { coupons } from '../../../store/coupons';
import { computed, onMounted, ref, watch } from 'vue';
import { useI18n } from 'vue-i18n';
import { useCoupons } from '../../../store/coupons/state';
import { useCustomer } from '../../../store/customer/state';
import NewCoupon from '../../../components/newCoupon.vue';
import { toast } from 'vue3-toastify';
import { scannerTopic } from '../../../features/usecases/scanner/events';
import { trolleyClient } from '@trolley/api-sdk';
import { useLoyaltyStore } from '../../../modules/loyalty/store/loyalty-store';
const tab = ref('general');
const { t } = useI18n();
const generalCoupons = computed(() => coupons().state.availableCoupons);
const customerCoupons = computed(() => useCustomer()?.customer?.discounts);
const hasCustomer = computed(() => useCustomer()?.customer !== null);
const selectedCoupon = coupons().state.selectedCoupon;
const manualCoupon = ref();
const isLoading = ref(false);
const isEmployeeDiscountApplied = ref(!!localStorage.getItem('employeeId'));
const employeeId = ref(localStorage.getItem('employeeId') ?? '');
onMounted(() => {
  scannerTopic.subscribe('SCANNED_COUPON', (code) => {
    manualCoupon.value = code;
    applyManualCoupon();
  });
});
async function applyManualCoupon() {
  isLoading.value = true;
  trolleyClient.discounts
    .postApiPosDiscountsGetByCode({
      requestBody: {
        code: manualCoupon.value,
      },
    })
    .then((res) => {
      if (res.data) {
        useCoupons().applyCoupon(res.data);
        manualCoupon.value = undefined;
      } else {
        toast.error('Coupon not found');
      }
    })
    .finally(() => {
      isLoading.value = false;
    });
}
watch(
  () => useCoupons().selectedCoupon,
  (coupon) => {
    if (!coupon) {
      employeeId.value = undefined;
      localStorage.removeItem('employeeId');
      isEmployeeDiscountApplied.value = false;
    }
  },
);
watch(
  () => globalStore.tab,
  () => {
    manualCoupon.value = undefined;
  },
);
</script>
<style scoped>
.tab {
  min-height: calc(100dvh - 450px);
}
.coupons-wrapper {
  height: calc(100dvh - 350px);
  overflow-y: scroll;
}
</style>
```

## File: src/views/actionPanels/cart/mainCartPanel.vue
```vue
<script setup lang="ts">
import LoyaltyMembership from '../../../modules/loyalty/components/cashier-view/loyalty-membership.vue';
import quickActionsVue from '../../../components/quickActions.vue';
import quickProductsAdd from '../../../components/quickProductsAdd.vue';
import coupons from './couponsView.vue';
import checkoutView from './checkoutView.vue';
import { globalStore } from '../../../store/global';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { trolleyClient } from '@trolley/api-sdk';
import { useQuickList } from '../../../modules/quick-list/store';
import { useLoyaltyStore } from '../../../modules/loyalty/store/loyalty-store';
</script>
<template>
  <v-window v-model="globalStore.tab" :touch="false">
    <v-window-item value="main">
    <quickProductsAdd
        :loading="useQuickList().loading"
        :availableProducts="useQuickList().items"
        :onSelect="
          (product) =>
            usePendingTransactionStore().itemsManager.addItem(product)
        "
        :onUPC="
          (upc) =>
            usePendingTransactionStore().itemsManager.addItemByUPC(
              upc,
              trolleyClient,
            )
        "
      />
      <LoyaltyMembership v-if="useLoyaltyStore().is_loyalty_enabled" />
      <quickActionsVue />
    </v-window-item>
    <v-window-item value="coupons">
      <coupons />
    </v-window-item>
    <v-window-item value="checkout">
      <checkoutView />
    </v-window-item>
  </v-window>
</template>
<style scoped></style>
```

## File: src/views/actionPanels/refundPanel.vue
```vue
<script lang="ts" setup>
import { globalStore } from '../../store/global';
import QuickProductsAdd from '../../components/quickProductsAdd.vue';
import { onMounted, ref } from 'vue';
import { trolleyClient } from '@trolley/api-sdk';
import { useRoute } from 'vue-router';
import { CompletedTransaction } from '@trolley/transactions';
import { useRefundTransactionStore } from '@trolley/transactions/vue';
import { useI18n } from 'vue-i18n';
import { toast } from 'vue3-toastify';
import router from '../../router';
import { useRefundBottomCards } from '../../store/bottom-cards';
globalStore.tab = 'Cart Items';
const loadingProducts = ref(true);
const transaction = ref();
const id = useRoute().query.id as string;
const resetRefundCalc = () => {
  useRefundBottomCards().isCalcReady = false;
  useRefundTransactionStore().itemsManager.totalDiscount = 0;
  useRefundTransactionStore().itemsManager.redeemedAmount = 0;
  useRefundTransactionStore().itemsManager.totalDue = 0;
};
onMounted(() => {
  useRefundTransactionStore().clear();
  resetRefundCalc();
  trolleyClient.refunds
    .getApiPosTransactionsByIdRefundDetails({
      id: id,
    })
    .then((response: any) => {
      transaction.value = response.data;
      const completedTransaction = new CompletedTransaction(response.data);
      useRefundTransactionStore().hydrate(completedTransaction);
    })
    .finally(() => {
      loadingProducts.value = false;
    });
});
const handleRefund = () => {
  showConfirmButtons.value = false;
  useRefundTransactionStore()
    .submit()
    .then(() => {
      resetRefundCalc();
      router.push({ name: 'cartPage' }).then(() => {
        toast.success('Refund successful');
      });
    });
};
const handleCancel = () => {
  showConfirmButtons.value = false;
  useRefundTransactionStore().itemsManager.unlock();
  resetRefundCalc();
};
const calcRefund = async () => {
  showConfirmButtons.value = true;
  useRefundTransactionStore().itemsManager.lock();
  const { data } =
    (await trolleyClient.refunds.postApiPosTransactionsRefundCalculate({
      requestBody: {
        transaction_code: useRefundTransactionStore().unique_code,
        items: useRefundTransactionStore().itemsManager.items,
      },
    })) as unknown as {
      data: {
        discount_amount: number;
        redeem_amount: number;
        refund_amount: number;
      };
    };
  useRefundTransactionStore().itemsManager.totalDiscount = data.discount_amount;
  useRefundTransactionStore().itemsManager.redeemedAmount = data.redeem_amount;
  useRefundTransactionStore().itemsManager.totalDue = data.refund_amount;
  useRefundBottomCards().isCalcReady = true;
};
const showConfirmButtons = ref(false);
const { t } = useI18n();
</script>
<template>
  <div class="d-flex flex-column">
    <quickProductsAdd
      height="calc(100dvh - 120px)"
      :loading="loadingProducts"
      :available-products="useRefundTransactionStore().availableItems"
      :onSelect="
        (product) => useRefundTransactionStore().itemsManager.addItem(product , product.targetUpc)
      "
      :onUPC="
        (upc) =>
          useRefundTransactionStore().itemsManager.addItemByUPC(
            upc,
            trolleyClient,
          )
      "
    />
    <v-btn
      :disabled="
        !useRefundTransactionStore().isProcessable ||
        useRefundTransactionStore().isSubmitting
      "
      color="primary"
      size="large"
      :loading="useRefundTransactionStore().isSubmitting"
      v-if="!showConfirmButtons"
      @click="calcRefund"
      class="w-100 text-uppercase mb-2"
    >
      {{ t('refund') }}
    </v-btn>
    <div class="w-100 d-flex" v-if="showConfirmButtons">
      <v-btn
        color="warning"
        size="large"
        class="flex-grow-1 me-1 text-uppercase mb-2"
        @click="handleCancel"
      >
        {{ t('cancel') }}
      </v-btn>
      <v-btn
        :disabled="!useRefundTransactionStore().isSubmittable"
        color="success"
        size="large"
        class="text-uppercase mb-2 flex-grow-1"
        @click="handleRefund"
      >
        {{ t('confirm') }}
      </v-btn>
    </div>
  </div>
</template>
⋮----
{{ t('refund') }}
⋮----
{{ t('cancel') }}
⋮----
{{ t('confirm') }}
⋮----
<style>
.receipt-wrapper {
  height: calc(100dvh - 390px);
  overflow-y: scroll;
}
input[type='date'] {
  display: block !important;
}
.flex-base-50 {
  flex-basis: calc(50% - 10px) !important;
}
</style>
```

## File: src/views/actionPanels/stashedCartsPanel.vue
```vue
<script setup lang="ts">
import { globalStore } from '../../store/global';
import CartPreview from '../../components/cartPreview.vue';
globalStore.tab = 'stashed_carts';
</script>
<template>
  <cart-preview />
</template>
<style scoped></style>
```

## File: src/views/actionPanels/transactionsPanel.vue
```vue
<script lang="ts" setup>
import CustomCard from '../../components/customs/customCard.vue';
import { globalStore } from '../../store/global';
import CustomReceipt from '../../components/customs/customReceipt.vue';
import DataPlaceholder from '../../components/dataPlaceholder.vue';
import { isTransactionPaid, isTransactionRefunded, transactions } from '../../store/transaction';
import { useTransactionStore } from '../../store/transaction/state';
import { isLocalRecord, trolleyClient } from '@trolley/api-sdk';
import { ref } from 'vue';
import CustomBtn from '../../components/customs/customBtn.vue';
import type { OrderData, Transaction } from '@trolley/types';
import router from '../../router';
import { toast } from 'vue3-toastify';
import { CompletedTransaction } from '@trolley/transactions';
import { useCurrentOrderStore } from '../../features/printing/state';
import { useI18n } from 'vue-i18n';
import { Item } from '@trolley/items';
globalStore.tab = 'transactions';
const receipt = transactions().state.singleTransaction;
const filter = transactions().state.transactionsFilter;
const printLoading = ref(false);
const refundLoading = ref(false);
const { t, locale } = useI18n();
function findTransactions() {
  useTransactionStore().loadTransactions();
}
const getTransaction = async (transactionId: number) => {
  const response =
    await trolleyClient.transactions.getApiPosTransactionsGetoneById({
      id: transactionId.toString(),
    });
  return response.data as OrderData;
};
const handlePrint = async (transactionId: number) => {
  printLoading.value = true;
  const transaction = await getTransaction(transactionId);
  printLoading.value = false;
  transaction.items = transaction.items.map((item: any) => {
    return new Item(item, item.targetUpc);
  });
  useCurrentOrderStore().state.order = transaction;
  new CompletedTransaction(transaction).printReceipt();
};
const handleRefund = async (receipt: Transaction) => {
  console.log('receipt', receipt);
  if (isLocalRecord(receipt)) {
    try {
      refundLoading.value = true;
      await trolleyClient.transactions.postApiPosSyncTransactions();
      refundLoading.value = false;
      await router.push({
        name: 'refundPage',
        query: { id: receipt?.id },
      });
    } catch (error) {
      refundLoading.value = false;
      toast.error("Couldn't reach the server. Please try again later.");
    }
  } else {
    await router.push({
      name: 'refundPage',
      query: { id: receipt?.id },
    });
  }
};
</script>
<template>
  <div class="d-flex flex-column">
    <v-sheet class="receipt-wrapper">
      <custom-receipt v-if="receipt" :receipt="receipt" />
      <data-placeholder :text="t('select_transaction')" v-else />
      <div
        v-if="receipt && isTransactionPaid(receipt)"
        class="d-flex pb-4 pl-2 pr-2"
      >
        <custom-btn
          class="me-1 flex-grow-1"
          icon="mdi mdi-reload"
          title="refund"
          color="error"
          variant="tonal"
          :disabled="printLoading"
          :loading="refundLoading"
          v-if="!isTransactionRefunded(receipt)"
          @click="handleRefund(receipt)"
        />
        <custom-btn
          class="flex-grow-1"
          icon="mdi mdi-printer"
          title="print"
          color="warning"
          variant="tonal"
          :disabled="printLoading"
          :loading="printLoading"
          @click="handlePrint(receipt.id)"
        />
      </div>
    </v-sheet>
    <custom-card
      class="mt-2"
      title="transactions_filter"
      icon="mdi mdi-filter"
      height="315"
    >
      <template #body>
        <div class="pa-2 bg-grey-lighten-3 rounded-lg pa-4">
          <v-form @submit.prevent="findTransactions">
            <v-sheet class="d-flex flex-wrap" color="transparent" elevation="0">
              <v-text-field
                class="flex-1-1-100 mb-2"
                variant="solo"
                density="compact"
                label="Transaction ID"
                hide-details
                flat
                v-model="filter.uniqueCode"
              ></v-text-field>
              <v-text-field
                type="date"
                density="compact"
                label="From Date"
                hide-details="auto"
                :flat="true"
                class="flex-1-1-5 mr-1 mb-2 flex-base-50"
                v-model="filter.fromDate"
              ></v-text-field>
              <v-text-field
                type="date"
                density="compact"
                label="To Date"
                hide-details="auto"
                :flat="true"
                class="flex-1-0 ml-1 mb-2 flex-base-50"
                v-model="filter.toDate"
              ></v-text-field>
              <div class="flex-1-1-100"></div>
              <v-text-field
                density="compact"
                label="Min. Amount"
                hide-details="auto"
                :flat="true"
                class="flex-1-0 mr-1 mb-2"
                v-model="filter.minAmount"
              ></v-text-field>
              <v-text-field
                density="compact"
                label="Max. Amount"
                hide-details="auto"
                :flat="true"
                class="flex-1-0 ml-1 mb-2"
                v-model="filter.maxAmount"
              />
              <v-select
                density="compact"
                label="Payment Method"
                :items="transactions().state.paymentMethods.value"
                hide-details="auto"
                :flat="true"
                :clearable="true"
                variant="solo"
                theme="light"
                class="flex-1-1-100 rounded-lg mb-2"
                v-model="filter.paymentMethodId"
              />
            </v-sheet>
            <div class="d-flex flex-row">
              <v-btn
                type="submit"
                variant="flat"
                color="primary"
                size="large"
                class="mt-2 flex-1-1 mr-1 text-uppercase"
              >
                {{ t('filter') }}
              </v-btn>
              <v-btn
                type="reset"
                variant="flat"
                color="default"
                size="large"
                class="mt-2 flex-1-1 ml-1 text-uppercase"
                @click="useTransactionStore().resetAndReload()"
              >
                {{ t('clear') }}
              </v-btn>
            </div>
          </v-form>
        </div>
      </template>
    </custom-card>
  </div>
</template>
⋮----
<template #body>
        <div class="pa-2 bg-grey-lighten-3 rounded-lg pa-4">
          <v-form @submit.prevent="findTransactions">
            <v-sheet class="d-flex flex-wrap" color="transparent" elevation="0">
              <v-text-field
                class="flex-1-1-100 mb-2"
                variant="solo"
                density="compact"
                label="Transaction ID"
                hide-details
                flat
                v-model="filter.uniqueCode"
              ></v-text-field>
              <v-text-field
                type="date"
                density="compact"
                label="From Date"
                hide-details="auto"
                :flat="true"
                class="flex-1-1-5 mr-1 mb-2 flex-base-50"
                v-model="filter.fromDate"
              ></v-text-field>
              <v-text-field
                type="date"
                density="compact"
                label="To Date"
                hide-details="auto"
                :flat="true"
                class="flex-1-0 ml-1 mb-2 flex-base-50"
                v-model="filter.toDate"
              ></v-text-field>
              <div class="flex-1-1-100"></div>
              <v-text-field
                density="compact"
                label="Min. Amount"
                hide-details="auto"
                :flat="true"
                class="flex-1-0 mr-1 mb-2"
                v-model="filter.minAmount"
              ></v-text-field>
              <v-text-field
                density="compact"
                label="Max. Amount"
                hide-details="auto"
                :flat="true"
                class="flex-1-0 ml-1 mb-2"
                v-model="filter.maxAmount"
              />
              <v-select
                density="compact"
                label="Payment Method"
                :items="transactions().state.paymentMethods.value"
                hide-details="auto"
                :flat="true"
                :clearable="true"
                variant="solo"
                theme="light"
                class="flex-1-1-100 rounded-lg mb-2"
                v-model="filter.paymentMethodId"
              />
            </v-sheet>
            <div class="d-flex flex-row">
              <v-btn
                type="submit"
                variant="flat"
                color="primary"
                size="large"
                class="mt-2 flex-1-1 mr-1 text-uppercase"
              >
                {{ t('filter') }}
              </v-btn>
              <v-btn
                type="reset"
                variant="flat"
                color="default"
                size="large"
                class="mt-2 flex-1-1 ml-1 text-uppercase"
                @click="useTransactionStore().resetAndReload()"
              >
                {{ t('clear') }}
              </v-btn>
            </div>
          </v-form>
        </div>
      </template>
⋮----
{{ t('filter') }}
⋮----
{{ t('clear') }}
⋮----
<style>
.receipt-wrapper {
  height: calc(100dvh - 390px);
  overflow-y: scroll;
}
input[type='date'] {
  display: block !important;
}
.flex-base-50 {
  flex-basis: calc(50% - 10px) !important;
}
</style>
```

## File: src/views/actionPanel.vue
```vue

```

## File: src/views/cartProducts.vue
```vue
<template>
  <section-title
    :title="t(sectionTitle ?? 'cart_items').toUpperCase()"
    icon="mdi mdi-cart-variant md-20"
  />
  <empty-screen v-if="activeTransaction.itemsManager.totalItems === 0" />
  <div
    v-dragscroll
    v-else
    :class="{
      'default-height-employee': !isClient,
      'default-height-client': isClient,
    }"
    class="filled-cart-options no-text-highlight"
  >
    <TransitionGroup name="list" tag="div" class="product-list">
      <cart-product-card
        v-for="(product, index) in activeTransaction.itemsManager.strategy.items"
        :key="product.key"
        :select-product="(id) => activeTransaction.itemsManager.addItem(id)"
        :un-select-product="(id) => activeTransaction.itemsManager.removeItemByIndex(id,index)"
        :increase-quantity="
          (id) => activeTransaction.itemsManager.increaseQuantity(id)
        "
        :decrease-quantity="
          (id) => activeTransaction.itemsManager.decreaseQuantity(id)
        "
        :product="product"
        :is-client="isClient"
        :is-disabled="activeTransaction.itemsManager.isLocked"
      />
    </TransitionGroup>
  </div>
</template>
<script setup lang="ts">
import CartProductCard from '../components/cartProductCard.vue';
import EmptyScreen from '../components/customs/emptyScreen.vue';
import SectionTitle from '../components/customs/sectionTitle.vue';
import type { ActiveTransaction } from '@trolley/transactions';
import { useI18n } from 'vue-i18n';
const { isClient, sectionTitle } = defineProps<{
  isClient?: boolean;
  sectionTitle?: string;
  activeTransaction: ActiveTransaction;
}>();
const { t } = useI18n();
</script>
<style scoped>
.empty-cart-options {
  background: #e0e0e0 no-repeat padding-box;
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.filled-cart-options {
  overflow-y: auto;
  padding-inline: 2px;
}
.filled-cart-options::-webkit-scrollbar {
  display: none;
}
.default-height-employee {
  height: calc(100dvh - 325px);
}
.default-height-client {
  height: calc(100dvh - 235px);
}
@media screen and (min-width: 1200px) {
  .default-height-client {
    height: calc(100dvh - 260px);
  }
}
.list-move {
  transition:
    transform 0.3s,
    opacity 0.3s;
}
.list-enter-active,
.list-leave-active {
  transition:
    opacity 0.2s,
    transform 0.2s;
}
.list-enter-from {
  opacity: 0;
  transform: translateX(30px);
}
.list-leave-to {
  opacity: 0;
  transform: translateY(10px);
}
.text {
  font-size: 12px;
  font-weight: normal;
}
</style>
```

## File: src/views/clientActionPanel.vue
```vue
<template>
  <client-membership />
  <banner-carousel
    v-if="useSettings()?.settings?.features['is_banners_enabled']"
  />
  <feedback-slider />
  <download-trolley
    v-if="useSettings()?.settings?.features['is_loyalty_enabled']"
  />
</template>
<script lang="ts" setup>
import FeedbackSlider from '../components/feedbackSlider.vue';
import DownloadTrolley from '../components/downloadTrolly.vue';
import BannerCarousel from '../modules/advertisement/banner-carousel.vue';
import { useSettings } from '../modules/settings/store';
import ClientMembership from '../modules/loyalty/components/client-view/client-membership.vue';
</script>
```

## File: src/views/sideNav.vue
```vue
<template>
  <v-card elevation="0" style="min-width: 60px">
    <v-layout style="min-height: 100dvh; max-height: 100dvh">
      <v-navigation-drawer permanent rail>
        <div
          class="d-flex flex-column"
          style="min-height: 100dvh; max-height: 100dvh"
        >
          <v-list color="transparent" density="compact" nav>
            <v-list-item
              v-for="(item, index) in TopList"
              :aria-label="item.title"
              :key="index"
              :to="item.link"
              class="d-flex flex-column justify-center align-center mt-4 transition"
              link
              :class="{ active: isActive(item) }"
            >
              <template #prepend>
                <span :class="{'active-icon': isActive(item)}"
                      class="nav-icon"
                      v-html="item.icon"></span>
              </template>
              <template #title>
                <p
                  :class="{
                    'text-weakTextColor': !isActive(item),
                    'text-primary': isActive(item),
                  }"
                  class="nav-items-title"
                >
                  {{ useI18n().t(item.title) }}
                </p>
              </template>
            </v-list-item>
          </v-list>
          <v-list class="mt-auto mb-4" color="transparent" nav>
            <KnetConnectionIndicator />
            <AppModeIndicator />
            <v-list-item
              v-for="(item, index) in BottomList"
              :key="index"
              class="d-flex flex-column justify-center align-center mt-4 transition"
              link
              @click="toggleCalculator(item)"
              :class="{ active: isActive(item) }"
            >
              <template #prepend>
                <span :class="{'active-icon': isActive(item)}"
                      class="nav-icon"
                      v-html="item.icon"></span>
              </template>
              <template #title>
                <p
                  :class="{
                    'text-weakTextColor': !isActive(item),
                    'text-primary': isActive(item),
                  }"
                  class="nav-items-title"
                >
                  {{ useI18n().t(item.title) }}
                </p>
              </template>
            </v-list-item>
          </v-list>
        </div>
      </v-navigation-drawer>
      <v-main style="height: 250px"></v-main>
    </v-layout>
  </v-card>
</template>
⋮----
<template #prepend>
                <span :class="{'active-icon': isActive(item)}"
                      class="nav-icon"
                      v-html="item.icon"></span>
              </template>
<template #title>
                <p
                  :class="{
                    'text-weakTextColor': !isActive(item),
                    'text-primary': isActive(item),
                  }"
                  class="nav-items-title"
                >
                  {{ useI18n().t(item.title) }}
                </p>
              </template>
⋮----
{{ useI18n().t(item.title) }}
⋮----
<template #prepend>
                <span :class="{'active-icon': isActive(item)}"
                      class="nav-icon"
                      v-html="item.icon"></span>
              </template>
<template #title>
                <p
                  :class="{
                    'text-weakTextColor': !isActive(item),
                    'text-primary': isActive(item),
                  }"
                  class="nav-items-title"
                >
                  {{ useI18n().t(item.title) }}
                </p>
              </template>
⋮----
{{ useI18n().t(item.title) }}
⋮----
<script>
import { useRoute } from 'vue-router';
import { globalStore } from '../store/global';
import { publish } from '@enegix/events';
import { AUTH_EVENTS } from '../modules/auth/events';
import { useClientScreen } from '../store/clientScreen';
import KnetConnectionIndicator from '../features/usecases/payments/knet/automatic/knet-connection-indicator.vue';
import BackendStatusIndicator from '../features/app-mode/backend-status-indicator.vue';
import { useI18n } from 'vue-i18n';
import { openClientPage } from '../utils/utils';
export default {
  components: {
    KnetConnectionIndicator,
    AppModeIndicator: BackendStatusIndicator,
  },
  data() {
    return {
      TopList: [
        {
          title: 'cart',
          icon: '<svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><circle cx="10" cy="28" r="2" fill="currentColor"/><circle cx="24" cy="28" r="2" fill="currentColor"/><path fill="currentColor" d="M28 7H5.82L5 2.8A1 1 0 0 0 4 2H0v2h3.18L7 23.2a1 1 0 0 0 1 .8h18v-2H8.82L8 18h18a1 1 0 0 0 1-.78l2-9A1 1 0 0 0 28 7m-2.8 9H7.62l-1.4-7h20.53Z"/></svg>',
          link: '/cart',
        },
        {
          title: 'stashed',
          icon: '<svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><path fill="currentColor" d="M25 2v7h7V2zm5 5h-3V4h3z"/><path fill="currentColor" d="M23 6h-7v12h12v-7h-5zm-2 10h-3v-3h3zm5-3v3h-3v-3zm-8-2V8h3v3z"/><path fill="currentColor" d="M26 20v2H6V8h8V6H6a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h20a2.003 2.003 0 0 0 2-2v-2zM2 26h28v2H2z"/></svg>',
          link: '/stashed',
        },
        {
          title: 'trans',
          icon: '<svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><path fill="currentColor" d="M21 16h2v2h-2zM9 16h8v2H9zm12-4h2v2h-2zM9 12h8v2H9zm0-4h14v2H9z"/><path fill="currentColor" d="M25 2H7a2 2 0 0 0-2 2v25a1 1 0 0 0 1 1h1a1 1 0 0 0 .8-.4l2.2-2.933l2.2 2.933a1.035 1.035 0 0 0 1.6 0l2.2-2.933l2.2 2.933a1.035 1.035 0 0 0 1.6 0l2.2-2.933l2.2 2.933a1 1 0 0 0 .8.4h1a1 1 0 0 0 1-1V4a2 2 0 0 0-2-2m0 25.333L22.8 24.4a1.035 1.035 0 0 0-1.6 0L19 27.333L16.8 24.4a1.035 1.035 0 0 0-1.6 0L13 27.333L10.8 24.4a1.035 1.035 0 0 0-1.6 0L7 27.333V4h18Z"/></svg>',
          link: '/trans',
        },
      ],
      BottomList: [
        {
          title: '2nd scrn',
          icon: '<svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><path fill="currentColor" d="M24 26h7v2h-7zm0-4h7v2h-7zm-3.586-10H25v-2h-8v8h2v-4.586L25.586 20L27 18.586z"/><path fill="currentColor" d="M7 7h22v12h2V7c0-1.102-.897-2-2-2H7c-1.103 0-2 .898-2 2v15c0 1.103.897 2 2 2h7v4h-4v2h12v-8H7zm13 21h-4v-4h4z"/><path fill="currentColor" d="M26 3V1H3c-1.103 0-2 .897-2 2v15h2V3z"/></svg>',
        },
        {
          title: 'exit',
          icon: '<svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32"><path fill="currentColor" d="m22.5 5.74l-1 1.73a11 11 0 1 1-11 0l-1-1.73a13 13 0 1 0 13 0"/><path fill="currentColor" d="M15 2h2v14h-2z"/></svg>',
        },
      ],
    };
  },
  methods: {
    useI18n,
    isActive(item) {
      const route = useRoute();
      return (
        route.path.includes(item.link) ||
        (item.title === 'calc' && globalStore.showCalculator)
      );
    },
    toggleCalculator(item) {
      if (item.title === '2nd scrn') {
        let clientScreen = useClientScreen();
        let time = new Date().getTime() - clientScreen.openLock;
        if (time > 3000) openClientPage();
      }
      if (item.title === 'exit') {
        publish(AUTH_EVENTS.END_SHIFT);
      }
    },
  },
};
</script>
<style lang="scss" scoped>
.nav-icon svg {
  color: #b5b5b5;
}
.nav-items-title {
  font-size: 9px;
}
.active {
  color: var(--v-theme-primary);
}
::v-deep(.nav-icon.active-icon svg ) {
  color: rgb(var(--v-theme-primary));
}
.transition {
  transition: all 1s;
}
</style>
```

## File: src/App.vue
```vue
<template>
  <router-view />
  <changeLangDemo />
  <transition name="freeze">
    <div v-if="isUIFrozen" class="freeze-ui">
      <transaction-subbmiting
        v-if="
          usePendingTransactionStore().isSubmitting &&
          usePendingTransactionStore().paymentsManager.hasPayment([
            PAYMENT_METHODS.AUTO_KNET,
            PAYMENT_METHODS.DEPRECATED_AUTO_KNET,
          ])
        "
      />
    </div>
  </transition>
  <sync-check-dialog v-if="!isClientHomePage" />
</template>
<script setup lang="ts">
import ChangeLangDemo from './components/changeLangDemo.vue';
import { computed, onMounted } from 'vue';
import SyncCheckDialog from './features/sync-check/sync-check-dialog.vue';
import { isClientHomePage } from './utils/path';
import preAuthFeatures from './features/pre-auth-features';
import { appStore } from './store/app-machine';
import TransactionSubbmiting from './components/transaction-subbmiting.vue';
import { usePendingTransactionStore } from '@trolley/transactions/vue';
import { PAYMENT_METHODS } from '@trolley/types';
const bytesToMb = (bytes: number | undefined) => {
  if (!bytes) return 0;
  return bytes / 1024 / 1024;
};
navigator.storage.estimate().then((estimate) => {
  console.log(`Quota: ${bytesToMb(estimate.quota)} MB`);
  console.log(`Usage: ${bytesToMb(estimate.usage)} MB`);
});
let usedBytes = new Blob(Object.values(localStorage)).size;
console.log(`LocalStorage Usage: ${bytesToMb(usedBytes)} MB`);
onMounted(() => {
  if (!isClientHomePage) {
    preAuthFeatures.bootstrap();
  }
});
const isUIFrozen = computed(() => appStore().state === 'loading');
</script>
<style scoped>
.freeze-ui {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 99;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgba(0, 0, 0, 0.2);
  backdrop-filter: blur(2px);
}
.freeze-enter-active,
.freeze-leave-active {
  transition:
    opacity 0.5s ease,
    backdrop-filter 0.5s ease;
}
.freeze-enter-from,
.freeze-leave-to {
  opacity: 0;
  backdrop-filter: blur(0);
}
</style>
```

## File: src/env.ts
```typescript
import { z } from 'zod';
import { removeAllSyncHealthChecks } from './utils/sync';
import { toast } from 'vue3-toastify';
```

## File: src/main.js
```javascript
const bootstrap = (component) => {
injectSDKConfig();
const app = createApp(component);
registerPlugins(app);
router.isReady().then(() => {
router.getRoutes().forEach((route) => {
⋮----
Object.values(route.components).forEach((comp) => {
⋮----
comp();
⋮----
const settingsStore = useSettings();
settingsStore?.fetchSettings();
app.component('barcode', VueBarcode);
app.mount('#app');
⋮----
if (!currentPath.includes('client') && typeof SharedWorker !== 'undefined') {
const worker = new SharedWorker('/multi-tab-worker.js');
worker.port.start();
worker.port.postMessage('check-open');
⋮----
bootstrap(MultiTab);
⋮----
window.focus();
⋮----
bootstrap(App);
⋮----
window.addEventListener('beforeunload', () => {
worker.port.close();
```

## File: src/main.spec.ts
```typescript
import { describe } from 'vitest';
```

## File: src/shims-vue.d.ts
```typescript

```

## File: .env.example
```
#VITE_APP_BASE_URL=https://wandering-crater-av9kog7djqb9.vapor-farm-g1.com
VITE_APP_BASE_URL=https://warm-willow-ejtl0a3x5gph.vapor-farm-c1.com
#VITE_APP_BASE_URL=https://trolley.solutions
VITE_POS_SYNC_KEY=kBXL7EvnS5nIKILwcmBpwWkV
VITE_OPENREPLAY_ENABLED=1
VITE_OPENREPLAY_KEY=fb2yB35vemv3RsSMOaAK
VITE_HONEYBADGER_KEY=hbp_EZhYhaJ9mOefYiT3CUOjyr49sYQ24g4cj7XM
VITE_SENTRY_DSN=https://abb123bc5acdf518d0a1c9fbb47a3127@sentry.enegix.xyz/2
VITE_IS_STAGING=0
```

## File: .eslintrc.json
```json
{
  "extends": [
    "../../.eslintrc.base.json",
    "plugin:vue/base",
    "eslint:recommended",
    "plugin:vue/vue3-essential"
  ],
  "ignorePatterns": [
    "*.js"
  ],
  "overrides": [
    {
      "files": [
        "*.ts",
        "*.tsx",
        "*.jsx",
        "*.vue"
      ],
      "rules": {
        "vue/multi-word-component-names": "off",
        "no-unused-vars": "off",
        "vue/valid-v-slot": "off"
      }
    }
  ],
  "parser": "vue-eslint-parser",
  "parserOptions": {
    "parser": "@typescript-eslint/parser",
    "ecmaVersion": 2020,
    "sourceType": "module"
  },
  "plugins": [
    "vue"
  ]
}
```

## File: Dockerfile
```dockerfile
FROM node:23-slim
COPY dist/apps/frontend/ /app/
EXPOSE 8000

CMD ["npx","servor","app", "index.html", "8080"]
```

## File: index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <script src="http://localhost:8098"></script>
    <meta charset="UTF-8"/>
    <link rel="icon" href="/logo.svg"/>
    <link rel="manifest" href="/manifest.json"/>
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>POS</title>
</head>
<body>
<script>
  (function() {
    const version = localStorage.getItem("appVersion");
    if (version && !location.pathname.startsWith(`/${version}/`)) {
      window.location.replace(`/${version}/`);
    }
  })();
</script>
<div id="app"></div>
<script type="module" src="src/main.js"></script>
</body>
</html>
```

## File: project.json
```json
{
  "name": "frontend",
  "$schema": "../../node_modules/nx/schemas/project-schema.json",
  "projectType": "application",
  "sourceRoot": "apps/frontend/src",
  "// targets": "to see all targets run: nx show project frontend --web",
  "targets": {
    "http-server": {
      "executor": "nx:run-commands",
      "options": {
        "command": "http-server -p 3000 -c-1 dist/apps/frontend"
      }
    }
  }
}
```

## File: tsconfig.app.json
```json
{
  "extends": "./tsconfig.json",
  "compilerOptions": {
    "outDir": "../../dist/out-tsc",
    "types": [
      "vite/client",
      "node"
    ],
    "noImplicitAny": false,
    "allowJs": true
  },
  "exclude": [
    "src/**/*.spec.ts",
    "src/**/*.test.ts",
    "src/**/*.spec.vue",
    "src/**/*.test.vue"
  ],
  "include": [
    "src/**/*.js",
    "src/**/*.jsx",
    "src/**/*.ts",
    "src/**/*.vue"
  ]
}
```

## File: tsconfig.json
```json
{
  "compilerOptions": {
    "allowJs": true,
    "esModuleInterop": false,
    "allowSyntheticDefaultImports": true,
    "strict": true,
    "jsx": "preserve",
    "jsxImportSource": "vue",
    "moduleResolution": "node",
    "resolveJsonModule": true,
    "verbatimModuleSyntax": true
  },
  "files": [],
  "include": [],
  "references": [
    {
      "path": "./tsconfig.app.json"
    },
    {
      "path": "./tsconfig.spec.json"
    }
  ],
  "extends": [
    "../../tsconfig.base.json",
  ]
}
```

## File: tsconfig.spec.json
```json
{
  "extends": "./tsconfig.json",
  "compilerOptions": {
    "outDir": "../../dist/out-tsc",
    "types": [
      "vitest/globals",
      "vitest/importMeta",
      "vite/client",
      "node",
      "vitest",
        "jest",
    ]
  },
  "include": [
    "vite.config.ts",
    "vitest.config.ts",
    "src/**/*.test.ts",
    "src/**/*.spec.ts",
    "src/**/*.test.tsx",
    "src/**/*.spec.tsx",
    "src/**/*.test.js",
    "src/**/*.spec.js",
    "src/**/*.test.jsx",
    "src/**/*.spec.jsx",
    "src/**/*.d.ts"
  ]
}
```

## File: vite.config.ts
```typescript
import { resolve } from 'path';
import { defineConfig } from 'vite';
import vue from '@vitejs/plugin-vue';
import { nxViteTsPaths } from '@nx/vite/plugins/nx-tsconfig-paths.plugin';
import vuetify, { transformAssetUrls } from 'vite-plugin-vuetify';
import ViteFonts from 'unplugin-fonts/vite';
import svgLoader from 'vite-svg-loader';
import { VitePWA } from 'vite-plugin-pwa';
import vueDevTools from 'vite-plugin-vue-devtools';
import { execSync } from 'child_process';
import { version as packageVersion } from '../../package.json';
import fg from 'fast-glob';
```
