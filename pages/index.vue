<script lang="ts">
    import { NConfigProvider, GlobalThemeOverrides } from 'naive-ui'
  
    const themeOverrides: GlobalThemeOverrides = {
      common: {
        primaryColor: '#FF0000'
      },
      Button: {
        textColor: '#FF0000'
      }
    }
  
    // ...
  </script>
  
  <template>
    <n-config-provider :theme-overrides="themeOverrides">
      <my-app />
    </n-config-provider>
  </template>