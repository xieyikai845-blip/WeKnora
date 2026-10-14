<template>
  <div class="login-layout workspace-login">
    <div v-if="false" class="animated-bg">
      <div class="knowledge-node node-1">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20" />
          <path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z" />
        </svg>
      </div>
      <div class="knowledge-node node-2">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z" />
        </svg>
      </div>
      <div class="knowledge-node node-3">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <path d="M12 2L2 7l10 5 10-5-10-5z" />
          <path d="M2 17l10 5 10-5" />
          <path d="M2 12l10 5 10-5" />
        </svg>
      </div>
      <div class="knowledge-node node-4">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <ellipse cx="12" cy="5" rx="9" ry="3" />
          <path d="M21 12c0 1.66-4 3-9 3s-9-1.34-9-3" />
          <path d="M3 5v14c0 1.66 4 3 9 3s9-1.34 9-3V5" />
        </svg>
      </div>
      <div class="knowledge-node node-5">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <circle cx="11" cy="11" r="8" />
          <path d="m21 21-4.35-4.35" />
        </svg>
      </div>
      <div class="knowledge-node node-6">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <path
            d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z" />
          <polyline points="3.27 6.96 12 12.01 20.73 6.96" />
          <line x1="12" y1="22.08" x2="12" y2="12" />
        </svg>
      </div>
      <div class="knowledge-node node-7">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z" />
          <polyline points="14 2 14 8 20 8" />
        </svg>
      </div>
      <div class="knowledge-node node-8">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2" />
          <circle cx="9" cy="7" r="4" />
          <path d="M23 21v-2a4 4 0 0 0-3-3.87" />
          <path d="M16 3.13a4 4 0 0 1 0 7.75" />
        </svg>
      </div>
      <div class="knowledge-node node-9">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z" />
        </svg>
      </div>
      <div class="knowledge-node node-10">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <circle cx="12" cy="12" r="3" />
          <path
            d="M12 1v6m0 6v6M5.64 5.64l4.24 4.24m4.24 4.24l4.24 4.24M1 12h6m6 0h6M5.64 18.36l4.24-4.24m4.24-4.24l4.24-4.24" />
        </svg>
      </div>
      <div class="knowledge-node node-11">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <path d="M9 11l3 3L22 4" />
          <path d="M21 12v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11" />
        </svg>
      </div>
      <div class="knowledge-node node-12">
        <svg class="node-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
          <polygon
            points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2" />
        </svg>
      </div>

      <svg class="knowledge-lines" viewBox="0 0 100 100" preserveAspectRatio="none">
        <line class="connection-line line-1" x1="20" y1="15" x2="35" y2="25" />
        <line class="connection-line line-2" x1="35" y1="25" x2="55" y2="20" />
        <line class="connection-line line-3" x1="55" y1="20" x2="85" y2="12" />
        <line class="connection-line line-4" x1="8" y1="35" x2="25" y2="45" />
        <line class="connection-line line-5" x1="25" y1="45" x2="65" y2="48" />
        <line class="connection-line line-6" x1="20" y1="60" x2="60" y2="75" />
        <line class="connection-line line-7" x1="20" y1="15" x2="20" y2="60" />
        <line class="connection-line line-8" x1="55" y1="20" x2="45" y2="50" />
        <line class="connection-line line-9" x1="65" y1="48" x2="90" y2="38" />
        <line class="connection-line line-10" x1="40" y1="70" x2="75" y2="80" />
        <line class="connection-line line-11" x1="35" y1="25" x2="25" y2="45" />
        <line class="connection-line line-12" x1="75" y1="30" x2="65" y2="48" />
      </svg>
    </div>

    <!-- Pure text brand: the login page intentionally does not use a logo image. -->
    <div class="brand-wordmark" aria-label="智川 X-Agent">
      <span class="brand-wordmark__zh">智川</span>
      <span class="brand-wordmark__divider"></span>
      <span class="brand-wordmark__en">X-Agent</span>
    </div>

    <!-- Header Links - Top Right -->
    <div class="header-links">
      <!-- 官方网站与 GitHub 入口按当前部署要求暂不展示。
      <a href="https://weknora.weixin.qq.com" target="_blank" class="header-link" :title="$t('common.website')">
        <svg width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"
          stroke-linecap="round">
          <circle cx="12" cy="12" r="10" />
          <line x1="2" y1="12" x2="22" y2="12" />
          <path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z" />
        </svg>
        <span class="link-text">{{ $t('common.website') }}</span>
      </a>

      <a href="https://github.com/Tencent/WeKnora" target="_blank" class="header-link" :title="$t('common.info')">
        <svg width="17" height="17" viewBox="0 0 24 24" fill="currentColor">
          <path
            d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0 0 24 12c0-6.63-5.37-12-12-12z" />
        </svg>
        <span class="link-text">GitHub</span>
      </a>
      -->

      <div class="language-switch">
        <button @click="toggleLanguageMenu" class="header-link" :title="currentLangOption?.label">
          <span class="lang-flag-icon">{{ currentLangOption?.flag }}</span>
          <span class="link-text">{{ currentLangOption?.shortLabel }}</span>
          <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"
            stroke-linecap="round">
            <polyline points="6 9 12 15 18 9" />
          </svg>
        </button>

        <!-- Language Dropdown -->
        <div v-if="showLanguageMenu" class="language-dropdown">
          <div v-for="lang in languageOptions" :key="lang.value" @click="selectLanguage(lang.value)"
            class="language-option" :class="{ active: currentLanguage === lang.value }">
            <span class="lang-flag">{{ lang.flag }}</span>
            <span class="lang-label">{{ lang.label }}</span>
            <span v-if="currentLanguage === lang.value" class="check-icon">✓</span>
          </div>
        </div>
      </div>
    </div>

    <!-- Product workspace: feature story and generated capability scenes. -->
    <section class="showcase-section">
      <div class="showcase-content">
        <div class="showcase-eyebrow">
          <span class="showcase-eyebrow__icon"><t-icon name="control-platform" /></span>
          Enterprise Knowledge Workspace
        </div>
        <h1 class="showcase-subtitle">{{ $t('platform.subtitle') }}</h1>
        <p class="showcase-description">{{ $t('platform.description') }}</p>

        <div class="feature-tags">
          <span class="tag"><t-icon name="file-paste" />{{ $t('platform.rag') }}</span>
          <span class="tag"><t-icon name="control-platform" />{{ $t('platform.agent') }}</span>
          <span class="tag"><t-icon name="books" />{{ $t('platform.wiki') }}</span>
          <span class="tag"><t-icon name="search" />{{ $t('platform.hybridSearch') }}</span>
        </div>

        <div class="feature-stage">
          <div class="feature-stage__rail" aria-hidden="true">
            <span class="feature-stage__rail-label">X-AGENT / CAPABILITIES</span>
            <span class="feature-stage__rail-count">03</span>
          </div>
          <swiper :modules="modules" :slides-per-view="1" :loop="true" :autoplay="{
            delay: 4800,
            disableOnInteraction: false,
          }" :effect="'fade'" :fade-effect="{ crossFade: true }"
            :pagination="{ clickable: true, dynamicBullets: false }" :speed="650" class="feature-swiper">
            <swiper-slide v-for="(slide, index) in slides" :key="index">
              <article class="feature-scene">
                <div class="feature-scene__copy">
                  <span class="feature-scene__index">0{{ index + 1 }}</span>
                  <h3>{{ slide.title }}</h3>
                  <p>{{ slide.description }}</p>
                  <div class="feature-scene__signal">
                    <span></span>
                    <span></span>
                    <span></span>
                  </div>
                </div>
                <div class="feature-scene__visual">
                  <img :src="slide.image" :alt="slide.title" class="slide-image" />
                </div>
              </article>
            </swiper-slide>
          </swiper>
        </div>
      </div>
    </section>

    <!-- Right Form Section -->
    <div class="form-section">
      <div class="form-panel">
        <!-- Login Card -->
        <div class="form-card" v-if="!isRegisterMode">
          <!-- invite_only 模式下共享链接停在登录卡，同样需要邀请上下文。 -->
          <div v-if="inviteLookup" class="invite-banner">
            <t-icon name="link" class="invite-banner__icon" />
            <div class="invite-banner__text">
              <div class="invite-banner__title">
                {{ $t('inviteRegister.bannerTitle', { tenant: inviteLookup.tenant_name || '' }) }}
              </div>
              <div class="invite-banner__hint">
                {{ $t('inviteRegister.bannerHintLogin') }}
              </div>
            </div>
          </div>
          <div v-else-if="inviteLookupError" class="invite-banner invite-banner--error">
            {{ inviteLookupError }}
          </div>
          <div class="form-header">
            <h2 class="form-title">{{ $t('auth.login') }}</h2>
            <p class="form-welcome">{{ $t('auth.subtitle') }}</p>
            <p v-if="registrationEnabled" class="form-hint">{{ $t('auth.loginHint') }}</p>
          </div>

          <div class="form-content">
            <t-form ref="formRef" :data="formData" :rules="formRules" @submit="handleLogin" layout="vertical"
              label-align="top">
              <t-form-item :label="$t('auth.email')" name="email">
                <t-input v-model="formData.email" :placeholder="$t('auth.emailPlaceholder')" type="text"
                  autocomplete="email" size="large" :disabled="loading" />
              </t-form-item>

              <t-form-item :label="$t('auth.password')" name="password">
                <t-input v-model="formData.password" :placeholder="$t('auth.passwordPlaceholder')" type="password"
                  autocomplete="current-password" size="large" :disabled="loading" @enter="handleLogin" />
              </t-form-item>

              <t-button type="submit" theme="primary" size="large" block :loading="loading" class="submit-button">
                {{ loading ? $t('auth.loggingIn') : $t('auth.login') }}
              </t-button>

              <div class="register-cta" v-if="registrationEnabled">
                <div class="register-cta__divider">
                  <span>{{ $t('auth.firstTime') }}</span>
                </div>
                <t-button theme="default" variant="outline" size="large" block class="register-cta__button"
                  :disabled="loading" @click="toggleMode">
                  {{ $t('auth.createAccount') }}
                </t-button>
              </div>

              <div v-if="oidcEnabled" class="oidc-divider">
                <span>{{ $t('auth.orContinueWith') }}</span>
              </div>

              <t-button v-if="oidcEnabled" theme="default" size="large" block :loading="oidcLoading" :disabled="loading"
                class="oidc-button" @click="handleOIDCLogin">
                {{ oidcLoading ? $t('auth.redirectingToOIDC') : oidcLoginText }}
              </t-button>
            </t-form>

            <!-- Features list -->
            <div class="login-features">
              <div class="feature-item">
                <span class="feature-icon">✓</span>
                <span class="feature-text">{{ $t('platform.multimodalParsing') }}</span>
              </div>
              <div class="feature-item">
                <span class="feature-icon">✓</span>
                <span class="feature-text">{{ $t('platform.hybridSearchEngine') }}</span>
              </div>
              <div class="feature-item">
                <span class="feature-icon">✓</span>
                <span class="feature-text">{{ $t('platform.ragQandA') }}</span>
              </div>
            </div>
          </div>
        </div>

        <!-- Register Card. Renders when the user is in register mode
             AND either self-service registration is enabled OR they
             arrived with a valid share-link token (which bypasses the
             invite_only gate). -->
        <div class="form-card" v-if="isRegisterMode && (registrationEnabled || inviteLookup)">
          <!-- Share-link banner: shown only when ?token= resolved to a
               real invitation row. Sits above the form header so the
               invitee instantly sees who invited them and into which
               workspace, without bumping the existing register UX. -->
          <div v-if="inviteLookup" class="invite-banner">
            <t-icon name="link" class="invite-banner__icon" />
            <div class="invite-banner__text">
              <div class="invite-banner__title">
                {{ $t('inviteRegister.bannerTitle', { tenant: inviteLookup.tenant_name || '' }) }}
              </div>
              <div class="invite-banner__hint">
                {{ $t('inviteRegister.bannerHint') }}
              </div>
            </div>
          </div>
          <div v-else-if="inviteLookupError" class="invite-banner invite-banner--error">
            {{ inviteLookupError }}
          </div>
          <div class="form-header">
            <h2 class="form-title">{{ $t('auth.createAccount') }}</h2>
            <p class="form-subtitle">{{ $t('auth.registerSubtitle') }}</p>
          </div>

          <div class="form-content">
            <t-form ref="registerFormRef" :data="registerData" :rules="registerRules" @submit="handleRegister"
              layout="vertical" label-align="top">
              <t-form-item :label="$t('auth.username')" name="username">
                <t-input v-model="registerData.username" :placeholder="$t('auth.usernamePlaceholder')" size="large"
                  :disabled="loading" />
              </t-form-item>

              <t-form-item :label="$t('auth.email')" name="email">
                <t-input v-model="registerData.email" :placeholder="$t('auth.emailPlaceholder')" type="text"
                  autocomplete="email" size="large" :disabled="loading" />
              </t-form-item>

              <t-form-item :label="$t('auth.password')" name="password">
                <t-input v-model="registerData.password" :placeholder="$t('auth.passwordPlaceholder')" type="password"
                  autocomplete="new-password" size="large" :disabled="loading" />
              </t-form-item>

              <t-form-item :label="$t('auth.confirmPassword')" name="confirmPassword">
                <t-input v-model="registerData.confirmPassword" :placeholder="$t('auth.confirmPasswordPlaceholder')"
                  type="password" autocomplete="new-password" size="large" :disabled="loading" @enter="handleRegister" />
              </t-form-item>

              <t-button type="submit" theme="primary" size="large" block :loading="loading" class="submit-button">
                {{ loading ? $t('auth.registering') : $t('auth.register') }}
              </t-button>
            </t-form>

            <div class="form-footer">
              <span>{{ $t('auth.haveAccount') }}</span>
              <a href="#" @click.prevent="toggleMode" class="link-button">
                {{ $t('auth.backToLogin') }}
              </a>
            </div>

            <!-- Features list for register -->
            <div class="login-features">
              <div class="feature-item">
                <span class="feature-icon">✓</span>
                <span class="feature-text">{{ $t('platform.independentTenant') }}</span>
              </div>
              <div class="feature-item">
                <span class="feature-icon">✓</span>
                <span class="feature-text">{{ $t('platform.fullApiAccess') }}</span>
              </div>
              <div class="feature-item">
                <span class="feature-icon">✓</span>
                <span class="feature-text">{{ $t('platform.knowledgeBaseManagement') }}</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref, reactive, nextTick, onMounted, onBeforeUnmount, computed } from 'vue'
import { useRoute, useRouter } from 'vue-router'
import { MessagePlugin } from 'tdesign-vue-next'
import { useRoleLabel } from '@/composables/useRoleLabel'
import { notifyLoginSuccess } from '@/utils/loginNotify'
import { newPasswordRules } from '@/utils/passwordPolicy'
import { Swiper, SwiperSlide } from 'swiper/vue'
import { Autoplay, EffectFade, Pagination } from 'swiper/modules'
import 'swiper/css'
import 'swiper/css/effect-fade'
import 'swiper/css/pagination'
import {
  login,
  register,
  getOIDCAuthorizationURL,
  getOIDCConfig,
  autoSetup,
  getAuthConfig,
  userInfoFromApi,
  getInvitationByToken,
  registerByInvite,
  type InviteLookup,
} from '@/api/auth'
import { useAuthStore } from '@/stores/auth'
import { useI18n } from 'vue-i18n'

// Purpose-built feature artwork for the login workspace.
import documentIntelligenceImage from '@/assets/img/login-document-intelligence.webp'
import knowledgeRetrievalImage from '@/assets/img/login-knowledge-retrieval.webp'
import agentOrchestrationImage from '@/assets/img/login-agent-orchestration.webp'

const router = useRouter()
const route = useRoute()
const authStore = useAuthStore()
const { t, tm, locale } = useI18n()
const { formatRole, roleIcon } = useRoleLabel()

// Swiper modules
const modules = [Autoplay, EffectFade, Pagination]

// Carousel slides data
const slides = [
  {
    image: documentIntelligenceImage,
    title: t('platform.carousel.smartDocRetrievalTitle'),
    description: t('platform.carousel.smartDocRetrievalDesc')
  },
  {
    image: knowledgeRetrievalImage,
    title: t('platform.carousel.hybridSearchTitle'),
    description: t('platform.carousel.hybridSearchDesc')
  },
  {
    image: agentOrchestrationImage,
    title: t('platform.carousel.agenticRagTitle'),
    description: t('platform.carousel.agenticRagDesc')
  }
]

// Form references
const formRef = ref()
const registerFormRef = ref()

// State management
const loading = ref(false)
const oidcLoading = ref(false)
const isRegisterMode = ref(false)
const showLanguageMenu = ref(false)
const oidcEnabled = ref(false)
const oidcProviderName = ref('')
// registrationEnabled defaults to true so that on first paint the Register
// link is visible; the actual mode is fetched from /auth/config in onMounted.
// In invite_only mode the link/card are hidden.
const registrationEnabled = ref(true)
const complexPasswordEnabled = ref(false)

// invite-link state. When the URL carries ?token=xxx we resolve it to
// the originating tenant + role and switch the form into a "register
// via invitation" mode. The token bypasses the normal invite_only
// gate — possessing it IS the authorisation. Submitting the register
// form with this set hits /auth/register-by-invite (auto-login on
// success) instead of /auth/register.
const inviteToken = ref('')
const inviteLookup = ref<InviteLookup | null>(null)
const inviteLookupError = ref('')
const inviteLookupLoading = ref(false)

// Language options
const languageOptions = [
  { value: 'zh-CN', label: '简体中文', shortLabel: '中文', flag: '🇨🇳' },
  { value: 'en-US', label: 'English', shortLabel: 'EN', flag: '🇺🇸' },
  { value: 'ru-RU', label: 'Русский', shortLabel: 'RU', flag: '🇷🇺' },
  { value: 'ko-KR', label: '한국어', shortLabel: '한국어', flag: '🇰🇷' }
]

const currentLanguage = computed(() => locale.value)
const oidcLoginText = computed(() => {
  if (oidcProviderName.value) {
    return t('auth.oidcLoginWithProvider', { provider: oidcProviderName.value })
  }
  return t('auth.oidcLogin')
})
const currentLangOption = computed(() => languageOptions.find(l => l.value === currentLanguage.value))

// Login form data
const formData = reactive<{ [key: string]: any }>({
  email: '',
  password: '',
})

// Register form data
const registerData = reactive<{ [key: string]: any }>({
  username: '',
  email: '',
  password: '',
  confirmPassword: ''
})

// Login form validation rules
const formRules = computed(() => ({
  email: [
    { required: true, message: t('auth.emailRequired'), type: 'error' },
    { email: true, message: t('auth.emailInvalid'), type: 'error' }
  ],
  password: [
    { required: true, message: t('auth.passwordRequired'), type: 'error' },
    { min: 8, message: t('auth.passwordMinLength'), type: 'error' },
    { max: 32, message: t('auth.passwordMaxLength'), type: 'error' }
  ],
}))

// Register form validation rules
const registerRules = computed(() => ({
  username: [
    { required: true, message: t('auth.usernameRequired'), type: 'error' },
    { min: 2, message: t('auth.usernameMinLength'), type: 'error' },
    { max: 20, message: t('auth.usernameMaxLength'), type: 'error' },
    {
      pattern: /^[a-zA-Z0-9_\u4e00-\u9fa5]+$/,
      message: t('auth.usernameInvalid'),
      type: 'error'
    }
  ],
  email: [
    { required: true, message: t('auth.emailRequired'), type: 'error' },
    { email: true, message: t('auth.emailInvalid'), type: 'error' }
  ],
  password: newPasswordRules(t, complexPasswordEnabled.value),
  confirmPassword: [
    { required: true, message: t('auth.confirmPasswordRequired'), type: 'error' },
    {
      validator: (val: string) => val === registerData.password,
      message: t('auth.passwordMismatch'),
      type: 'error'
    }
  ]
}))

// Toggle login/register mode
const toggleMode = () => {
  isRegisterMode.value = !isRegisterMode.value

  Object.keys(registerData).forEach(key => {
    (registerData as any)[key] = ''
  })
}

// Toggle language menu
const toggleLanguageMenu = () => {
  showLanguageMenu.value = !showLanguageMenu.value
}

// Select language
const selectLanguage = (lang: string) => {
  locale.value = lang
  localStorage.setItem('locale', lang)
  showLanguageMenu.value = false
  MessagePlugin.success(t('language.languageSaved'))
}

// Close language menu when clicking outside
const handleClickOutside = (event: MouseEvent) => {
  const target = event.target as HTMLElement
  if (!target.closest('.language-switch')) {
    showLanguageMenu.value = false
  }
}

// Add click outside listener
onMounted(() => {
  document.addEventListener('click', handleClickOutside)
})

onBeforeUnmount(() => {
  document.removeEventListener('click', handleClickOutside)
})

const persistLoginResponse = async (response: any, skipRedirect = false) => {
  // Backend renamed `tenant` to `active_tenant` and added `memberships`
  // when tenant-level RBAC landed (issue #1303). The two are otherwise
  // identical — `active_tenant` is the tenant whose ID is encoded in the
  // JWT, defaulting to the user's home tenant on a fresh login.
  const activeTenant = response.active_tenant || response.tenant
  if (response.user && response.token) {
    // user.tenant_id must be the user's HOME tenant (the immutable row
    // on the users table); useHomeTenant() and the home-badge logic both
    // assume so. The ACTIVE tenant (which can differ from home when the
    // server honoured a remembered last-active-tenant preference) is
    // expressed separately via setSelectedTenant below.
    const homeTenantIdRaw = response.user.tenant_id ?? activeTenant?.id ?? ''
    authStore.setUser(userInfoFromApi(response.user, homeTenantIdRaw))
    authStore.setToken(response.token)
    if (response.refresh_token) {
      authStore.setRefreshToken(response.refresh_token)
    }
    if (activeTenant) {
      authStore.setTenant({
        id: String(activeTenant.id) || '',
        name: activeTenant.name || '',
        owner_id: response.user.id || '',
        created_at: activeTenant.created_at || new Date().toISOString(),
        updated_at: activeTenant.updated_at || new Date().toISOString()
      })
    } else {
      authStore.setTenant(null)
    }
    if (Array.isArray(response.memberships)) {
      authStore.setMemberships(response.memberships)
    }
    // If the backend dropped us into a non-home tenant (honoured a
    // remembered "last active tenant" preference), set the override so
    // subsequent requests carry X-Tenant-ID and the UI stays consistent.
    // Otherwise clear any stale override left in localStorage by a
    // previous session for a different account.
    const activeIdNum = Number(activeTenant?.id)
    const homeIdNum = Number(homeTenantIdRaw)
    if (Number.isFinite(activeIdNum) && Number.isFinite(homeIdNum) && activeIdNum !== homeIdNum) {
      authStore.setSelectedTenant(activeIdNum, activeTenant?.name || null)
    } else {
      authStore.setSelectedTenant(null, null)
    }
  }

  // Pull runtime capabilities (including whether ordinary users may create
  // workspaces) before entering the main UI so create actions never flash
  // briefly when the deployment is invitation-only.
  await authStore.refreshFromAuthMe()
  await nextTick()
  if (skipRedirect) return
  router.replace(authStore.hasValidTenant ? '/platform/knowledge-bases' : '/onboarding/workspace')
}

const getBackendOIDCRedirectURI = () => `${window.location.origin}/api/v1/auth/oidc/callback`

const loadOIDCConfig = async () => {
  try {
    const response = await getOIDCConfig()
    oidcEnabled.value = !!response.success && !!response.enabled
    oidcProviderName.value = response.provider_display_name || ''
  } catch {
    oidcEnabled.value = false
    oidcProviderName.value = ''
  }
}

// loadAuthConfig fetches /auth/config and caches whether self-service
// registration is allowed. Failures fall back to "enabled" so a transient
// network glitch doesn't lock new users out of an open deployment.
const loadAuthConfig = async () => {
  try {
    const response = await getAuthConfig()
    registrationEnabled.value = response.registration_mode !== 'invite_only'
    complexPasswordEnabled.value = response.complex_password_enabled
  } catch {
    registrationEnabled.value = true
    complexPasswordEnabled.value = false
  }
}

const handleOIDCLogin = async () => {
  try {
    oidcLoading.value = true
    const response = await getOIDCAuthorizationURL(getBackendOIDCRedirectURI())
    const authorizationURL = response.authorization_url

    if (!response.success || !authorizationURL) {
      MessagePlugin.error(response.message || t('auth.oidcLoginFailed'))
      return
    }

    // 跳转 IdP 会丢失 URL 中的 token，暂存到 sessionStorage，回调后由 App.vue 兑换。
    if (inviteToken.value) {
      sessionStorage.setItem('weknora_pending_invite_token', inviteToken.value)
    }
    window.location.href = authorizationURL
  } catch (error: any) {
    console.error('OIDC 登录跳转失败:', error)
    MessagePlugin.error(error.message || t('auth.oidcLoginFailed'))
  } finally {
    oidcLoading.value = false
  }
}

// 用 token 加入空间并进入应用。会话此时已有效，故即便 token 失效也照常进入（避免困在登录页）。
const acceptAndEnter = async (token: string) => {
  loading.value = true
  try {
    const result = await authStore.acceptInvitationByTokenAndRefresh(token)
    if (result.ok) {
      MessagePlugin.success(t('inviteRegister.joined'))
    } else {
      MessagePlugin.warning(t('inviteRegister.invalidBody'))
    }
  } catch {
    MessagePlugin.warning(t('inviteRegister.invalidBody'))
  } finally {
    loading.value = false
    await nextTick()
    router.replace('/platform/knowledge-bases')
  }
}

// Handle login
const handleLogin = async () => {
  try {
    const valid = await formRef.value?.validate()
    if (valid !== true) return

    loading.value = true

    const response = await login({
      email: formData.email,
      password: formData.password,
    })

    if (response.success) {
      if (inviteToken.value) {
        // 从邀请链接登录：持久化会话后兑换 token 并进入对应空间。
        await persistLoginResponse(response, true)
        await acceptAndEnter(inviteToken.value)
        return
      }
      await persistLoginResponse(response)
      notifyLoginSuccess(response, t, tm, formatRole, roleIcon)
    } else {
      MessagePlugin.error(response.message || t('auth.loginError'))
    }
  } catch (error: any) {
    console.error('登录错误:', error)
    MessagePlugin.error(error.message || t('auth.loginErrorRetry'))
  } finally {
    loading.value = false
  }
}

// Handle registration. Dispatches based on whether the user arrived
// with a share-link token: with token -> register-by-invite (auto-
// login on success); without -> the normal self-service register
// (drops back to the login form for the user to sign in).
const handleRegister = async () => {
  try {
    const valid = await registerFormRef.value?.validate()
    if (valid !== true) return

    loading.value = true

    if (inviteToken.value) {
      const response = await registerByInvite({
        token: inviteToken.value,
        username: registerData.username,
        email: registerData.email,
        password: registerData.password,
      })
      if (!response.success) {
        MessagePlugin.error(response.message || t('auth.registerFailed'))
        return
      }
      MessagePlugin.success(t('auth.registerSuccess'))
      // register-by-invite returns the same shape as login (token +
      // active_tenant + memberships), so reuse the login persistence
      // path — same store writes, same redirect target.
      await persistLoginResponse(response)
      return
    }

    const response = await register({
      username: registerData.username,
      email: registerData.email,
      password: registerData.password
    })

    if (response.success) {
      MessagePlugin.success(t('auth.registerSuccess'))

      // Switch to login mode and fill in email
      isRegisterMode.value = false
      formData.email = registerData.email

      // Clear register form
      Object.keys(registerData).forEach(key => {
        (registerData as any)[key] = ''
      })
    } else {
      MessagePlugin.error(response.message || t('auth.registerFailed'))
    }
  } catch (error: any) {
    console.error('注册错误:', error)
    MessagePlugin.error(error.message || t('auth.registerError'))
  } finally {
    loading.value = false
  }
}

// Check if already logged in; for lite edition, attempt transparent auto-setup
onMounted(async () => {
  // Share-link landing: ?token=xxx switches the form into invite-
  // register mode before any other auto-flow (logged-in redirect /
  // auto-setup / OIDC) gets a chance to redirect. Resolution failure
  // surfaces inline; the user can still log in normally if they
  // already have an account. We check this BEFORE the isLoggedIn
  // redirect so an existing session doesn't bounce the user to
  // /platform (and possibly back to /login if the session is stale),
  // dropping the invite token along the way.
  const tokenFromQuery = String(route.query.token || '').trim()
  if (tokenFromQuery) {
    inviteToken.value = tokenFromQuery
    inviteLookupLoading.value = true
    // 1. 先校验 token：无效/过期则停在登录页报错，不进注册模式。
    try {
      const resp = await getInvitationByToken(tokenFromQuery)
      if (resp.success && resp.data) {
        inviteLookup.value = resp.data
      } else {
        inviteLookupError.value = resp.message || t('inviteRegister.invalidBody')
        loadOIDCConfig()
        loadAuthConfig()
        return
      }
    } catch {
      inviteLookupError.value = t('inviteRegister.invalidBody')
      loadOIDCConfig()
      loadAuthConfig()
      return
    } finally {
      inviteLookupLoading.value = false
    }

    // 2. 已登录则直接兑换 token 进入空间（两种模式通用）。
    if (authStore.isLoggedIn && (await authStore.refreshFromAuthMe())) {
      await acceptAndEnter(tokenFromQuery)
      return
    }

    // 3. 未登录：按注册模式决定界面。invite_only 停在登录页、登录后再兑换；self_serve 保持注册流程。
    const cfg = await getAuthConfig()
    const inviteOnly = cfg.registration_mode === 'invite_only'
    registrationEnabled.value = !inviteOnly
    isRegisterMode.value = !inviteOnly
    loadOIDCConfig()
    return
  }

  if (authStore.isLoggedIn) {
    router.replace('/platform/knowledge-bases')
    return
  }

  const AUTO_SETUP_FAILED_KEY = 'weknora_auto_setup_failed'
  if (localStorage.getItem(AUTO_SETUP_FAILED_KEY) !== 'true') {
    try {
      const response = await autoSetup()
      if (response.success) {
        authStore.setLiteMode(true)
        await persistLoginResponse(response)
        return
      } else {
        localStorage.setItem(AUTO_SETUP_FAILED_KEY, 'true')
      }
    } catch {
      localStorage.setItem(AUTO_SETUP_FAILED_KEY, 'true')
    }
  }

  loadOIDCConfig()
  loadAuthConfig()
})
</script>

<style lang="less" scoped>
.login-layout {
  display: flex;
  width: 100%;
  min-height: 100%;
  overflow: hidden;
  position: relative;
  background: linear-gradient(225deg, #022c22 0%, #064e3b 15%, #065f46 25%, #047857 38%, #059669 50%, #07C05F 65%, #10B981 78%, #34D399 90%, #6EE7B7 100%);

  &::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: radial-gradient(circle at 20% 50%, rgba(255, 255, 255, 0.06) 0%, transparent 50%),
      radial-gradient(circle at 80% 50%, rgba(255, 255, 255, 0.04) 0%, transparent 50%);
    pointer-events: none;
  }
}

.animated-bg {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  pointer-events: none;
  z-index: 1;
  overflow: hidden;
  contain: strict;
}

.knowledge-node {
  position: absolute;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.15);
  border: 2px solid rgba(255, 255, 255, 0.3);
  box-shadow:
    0 0 15px rgba(255, 255, 255, 0.35),
    0 0 30px rgba(16, 185, 129, 0.2),
    inset 0 0 8px rgba(255, 255, 255, 0.1);
  display: flex;
  align-items: center;
  justify-content: center;
  animation: nodePulse 5s infinite ease-in-out;
  will-change: transform, opacity;
}

.node-icon {
  width: 20px;
  height: 20px;
  color: rgba(255, 255, 255, 0.9);
}

.node-1 {
  top: 15%;
  left: 20%;
  animation-delay: 0s;
}

.node-2 {
  top: 25%;
  left: 35%;
  animation-delay: 0.5s;
}

.node-3 {
  top: 20%;
  left: 55%;
  animation-delay: 1s;
}

.node-4 {
  top: 30%;
  left: 75%;
  animation-delay: 1.5s;
}

.node-5 {
  top: 45%;
  left: 25%;
  animation-delay: 2s;
}

.node-6 {
  top: 50%;
  left: 45%;
  animation-delay: 2.5s;
}

.node-7 {
  top: 48%;
  left: 65%;
  animation-delay: 3s;
}

.node-8 {
  top: 60%;
  left: 20%;
  animation-delay: 0.3s;
}

.node-9 {
  top: 12%;
  right: 15%;
  animation-delay: 1.8s;
}

.node-10 {
  top: 38%;
  right: 10%;
  animation-delay: 2.3s;
}

.node-11 {
  top: 70%;
  left: 40%;
  animation-delay: 0.8s;
}

.node-12 {
  top: 65%;
  left: 80%;
  animation-delay: 1.3s;
}

@keyframes nodePulse {

  0%,
  100% {
    transform: scale(1);
    opacity: 0.65;
  }

  50% {
    transform: scale(1.08);
    opacity: 0.9;
  }
}

.knowledge-lines {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 0.35;
}

.connection-line {
  stroke: rgba(255, 255, 255, 0.5);
  stroke-width: 1.5;
  stroke-dasharray: 6, 3;
  stroke-linecap: round;
  animation: lineFlow 10s infinite linear;
  will-change: stroke-dashoffset;
}

.line-1 {
  animation-delay: 0s;
}

.line-2 {
  animation-delay: 0.5s;
}

.line-3 {
  animation-delay: 1s;
}

.line-4 {
  animation-delay: 0.3s;
}

.line-5 {
  animation-delay: 0.8s;
}

.line-6 {
  animation-delay: 1.3s;
}

.line-7 {
  animation-delay: 1.8s;
}

.line-8 {
  animation-delay: 2.3s;
}

.line-9 {
  animation-delay: 0.2s;
}

.line-10 {
  animation-delay: 0.7s;
}

.line-11 {
  animation-delay: 0.9s;
}

.line-12 {
  animation-delay: 1.5s;
}

@keyframes lineFlow {
  0% {
    stroke-dashoffset: 0;
  }

  100% {
    stroke-dashoffset: 18;
  }
}

@media (prefers-reduced-motion: reduce) {
  .knowledge-node {
    animation: none;
    opacity: 0.65;
  }

  .connection-line {
    animation: none;
  }
}

/* Left Showcase Section */
.showcase-section {
  flex: 0 0 52%;
  display: flex;
  align-items: flex-end;
  padding: 100px 30px 100px 50px;
  box-sizing: border-box;
  position: relative;
}

.showcase-content {
  width: 100%;
  max-width: 600px;
  position: relative;
  z-index: 2;
  display: flex;
  flex-direction: column;
  margin-bottom: 60px;
}

.showcase-subtitle {
  margin-top: 0;
  font-size: 22px;
  color: rgba(255, 255, 255, 0.95);
  margin: 0 0 8px 0;
  font-family: var(--app-font-family);
  line-height: 1.4;
  font-weight: 500;
}

.showcase-description {
  font-size: 15px;
  color: rgba(255, 255, 255, 0.8);
  margin: 0 0 28px 0;
  font-family: var(--app-font-family);
  line-height: 1.5;
}

.feature-tags {
  display: flex;
  gap: 12px;
  margin-bottom: 40px;
  flex-wrap: wrap;
}

.tag {
  display: inline-block;
  padding: 8px 20px;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 20px;
  color: var(--td-text-color-anti);
  font-size: 14px;
  font-weight: 500;
  font-family: var(--app-font-family);
}

/* Carousel */
.carousel-container {
  width: 100%;
  margin-top: 48px;
}

.screenshot-swiper {
  width: 100%;
  border-radius: 16px;
  overflow: hidden;
  box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
  padding-bottom: 40px;

  :deep(.swiper-wrapper) {
    transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  }

  :deep(.swiper-pagination) {
    bottom: 15px !important;
    z-index: 10;
  }

  :deep(.swiper-pagination-bullet) {
    width: 10px;
    height: 10px;
    background: rgba(255, 255, 255, 0.5);
    opacity: 1;
    transition: all 0.3s ease;
    margin: 0 6px !important;
  }

  :deep(.swiper-pagination-bullet-active) {
    background: var(--td-bg-color-container);
    width: 28px;
    border-radius: 5px;
  }
}

.slide-content {
  width: 100%;
  height: 100%;
  background: var(--td-bg-color-container);
  border-radius: 16px;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
}

.slide-image {
  width: 100%;
  height: 100%;
  display: block;
  object-fit: contain;
}

/* Right Form Section */
.form-section {
  flex: 0 0 48%;
  display: flex;
  align-items: flex-end;
  justify-content: center;
  padding: 40px 50px 100px 30px;
  box-sizing: border-box;
  position: relative;
}

.form-panel {
  width: 100%;
  max-width: 480px;
  margin-bottom: 60px;
  position: relative;
  z-index: 2;
}

.header-logo {
  position: fixed;
  top: 32px;
  left: 50px;
  z-index: 100;
  cursor: pointer;

  .logo-image {
    width: 120px;
    height: auto;
  }
}

.header-links {
  position: fixed;
  top: 28px;
  right: 28px;
  display: flex;
  align-items: center;
  gap: 10px;
  z-index: 100;
}

.header-link {
  display: flex;
  align-items: center;
  gap: 7px;
  padding: 9px 15px;
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.2);
  border: 1px solid rgba(255, 255, 255, 0.25);
  color: var(--td-text-color-anti);
  text-decoration: none;
  font-size: 13px;
  font-weight: 600;
  font-family: var(--app-font-family);
  letter-spacing: 0.2px;
  cursor: pointer;
  position: relative;

  svg {
    flex-shrink: 0;
  }

  .link-text {
    line-height: 1;
  }

  &:hover {
    background: rgba(255, 255, 255, 0.3);
    border-color: rgba(255, 255, 255, 0.4);
    color: var(--td-text-color-anti);
  }
}

.language-switch {
  position: relative;

  button {
    background: rgba(255, 255, 255, 0.2);
    border: 1px solid rgba(255, 255, 255, 0.25);
    color: var(--td-text-color-anti);

    .lang-flag-icon {
      font-size: 16px;
      line-height: 1;
      flex-shrink: 0;
    }

    &:hover {
      background: rgba(255, 255, 255, 0.3);
      border-color: rgba(255, 255, 255, 0.4);
    }

    svg:last-child {
      margin-left: 2px;
      flex-shrink: 0;
    }
  }
}

.language-dropdown {
  position: absolute;
  top: calc(100% + 8px);
  right: 0;
  min-width: 160px;
  background: rgba(255, 255, 255, 0.97);
  border: 1px solid var(--td-component-stroke);
  border-radius: 8px;
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.12);
  overflow: hidden;
  z-index: 1000;
}

.language-option {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 10px 14px;
  cursor: pointer;
  font-size: 13px;
  font-family: var(--app-font-family);
  color: var(--td-text-color-primary);

  .lang-flag {
    font-size: 16px;
    flex-shrink: 0;
  }

  .lang-label {
    flex: 1;
  }

  .check-icon {
    color: var(--td-success-color);
    font-weight: 700;
    font-size: 14px;
    flex-shrink: 0;
  }

  &:hover {
    background: var(--td-bg-color-secondarycontainer);
  }

  &.active {
    background: var(--td-success-color-light);
    color: var(--td-brand-color-active);
  }
}

.form-card {
  background: rgba(255, 255, 255, 0.97);
  border-radius: 16px;
  padding: 40px;
  box-shadow: 0 10px 40px rgba(0, 0, 0, 0.15);
  box-sizing: border-box;
  border: none;
  width: 100%;
}

/* Share-link invitation banner. Sits above the register form when the
 * user arrived via /register?token=xxx; gives them confirmation of who
 * invited them before they fill anything in. Subtle, neutral card —
 * the page background is heavily brand-coloured already, so a loud
 * tinted banner clashes; we lean on the form's own surface tokens. */
.invite-banner {
  display: flex;
  align-items: flex-start;
  gap: 10px;
  padding: 12px 14px;
  margin-bottom: 20px;
  border-radius: 10px;
  background: var(--td-bg-color-container-hover, rgba(0, 0, 0, 0.03));
  border: 1px solid var(--td-component-stroke);
  color: var(--td-text-color-primary);
}

.invite-banner__icon {
  margin-top: 2px;
  font-size: 18px;
  flex-shrink: 0;
  color: var(--td-text-color-secondary);
}

.invite-banner__text {
  display: flex;
  flex-direction: column;
  gap: 2px;
  min-width: 0;
}

.invite-banner__title {
  font-size: 14px;
  font-weight: 600;
  line-height: 1.4;
  color: var(--td-text-color-primary);
}

.invite-banner__hint {
  font-size: 12px;
  color: var(--td-text-color-secondary);
  line-height: 1.5;
}

.invite-banner--error {
  background: var(--td-error-color-1, rgba(220, 38, 38, 0.06));
  border-color: var(--td-error-color-3, rgba(220, 38, 38, 0.2));
  color: var(--td-error-color, #b91c1c);
  font-size: 13px;
}

.form-header {
  text-align: center;
  margin-bottom: 32px;
}

.form-title {
  font-size: 24px;
  font-weight: 600;
  color: var(--td-text-color-primary);
  margin: 0 0 6px 0;
  font-family: var(--app-font-family);
}

.form-welcome {
  font-size: 13px;
  color: var(--td-text-color-secondary);
  margin: 0;
  font-family: var(--app-font-family);
}

.form-hint {
  margin: 10px 0 0;
  padding: 8px 12px;
  border-radius: 8px;
  background: var(--td-success-color-light, rgba(7, 192, 95, 0.08));
  color: var(--td-brand-color-active);
  font-size: 12.5px;
  line-height: 1.5;
  font-family: var(--app-font-family);
}

/* 注册入口：从底部小字链接升级为带分隔线的醒目次级按钮，
   让首次访客一眼就能找到「创建账户」。 */
.register-cta {
  margin-top: 8px;

  &__divider {
    position: relative;
    text-align: center;
    margin: 4px 0 14px;
    color: var(--td-text-color-secondary);
    font-size: 13px;
    font-family: var(--app-font-family);

    span {
      position: relative;
      z-index: 1;
      padding: 0 12px;
      background: rgba(255, 255, 255, 0.97);
    }

    &::before {
      content: '';
      position: absolute;
      left: 0;
      right: 0;
      top: 50%;
      border-top: 1px solid var(--td-component-stroke);
    }
  }

  &__button {
    height: 46px;
    border-radius: 8px;
    font-size: 15px;
    font-weight: 500;
    border-color: var(--td-brand-color);
    color: var(--td-brand-color);

    &:hover {
      border-color: var(--td-brand-color-active);
      color: var(--td-brand-color-active);
      background: var(--td-success-color-light, rgba(7, 192, 95, 0.08));
    }
  }
}

.form-subtitle {
  font-size: 13px;
  color: var(--td-text-color-secondary);
  margin: 0;
  font-family: var(--app-font-family);
}

.form-content {
  :deep(.t-form-item__label) {
    font-size: 14px;
    color: var(--td-text-color-primary);
    font-weight: 500;
    margin-bottom: 8px;
    font-family: var(--app-font-family);
    display: block;
    text-align: left;
  }

  :deep(.t-input) {
    border: 1px solid var(--td-component-stroke);
    border-radius: 8px;
    background: var(--td-bg-color-container);
    transition: all 0.2s;

    &:focus-within {
      border-color: var(--td-brand-color);
      box-shadow: 0 0 0 3px rgba(7, 192, 95, 0.1);
    }

    &:hover {
      border-color: var(--td-brand-color);
    }

    .t-input__inner {
      border: none !important;
      box-shadow: none !important;
      outline: none !important;
      background: transparent;
      font-size: 15px;
      font-family: var(--app-font-family);

      &:focus {
        border: none !important;
        box-shadow: none !important;
        outline: none !important;
      }
    }

    .t-input__wrap {
      border: none !important;
      box-shadow: none !important;
    }
  }

  :deep(.t-form-item) {
    margin-bottom: 18px;

    &:last-child {
      margin-bottom: 0;
    }
  }

  :deep(.t-form-item__control) {
    width: 100%;
  }
}

.submit-button {
  height: 46px;
  border-radius: 8px;
  font-size: 16px;
  font-weight: 500;
  font-family: var(--app-font-family);
  margin: 20px 0 16px 0;
}

.oidc-divider {
  position: relative;
  margin: 4px 0 6px;
  text-align: center;
  color: var(--td-text-color-placeholder);
  font-size: 12px;

  span {
    position: relative;
    z-index: 1;
    padding: 0 12px;
    background: rgba(255, 255, 255, 0.95);
  }

  &::before {
    content: '';
    position: absolute;
    left: 0;
    right: 0;
    top: 50%;
    border-top: 1px solid var(--td-component-stroke);
  }
}

.oidc-button {
  height: 46px;
  border-radius: 8px;
  font-size: 15px;
  font-weight: 500;
}

.form-footer {
  text-align: center;
  font-size: 14px;
  color: var(--td-text-color-secondary);
  font-family: var(--app-font-family);
  margin-top: 16px;
  padding-bottom: 16px;
  border-bottom: 1px solid var(--td-component-stroke);

  .link-button {
    color: var(--td-brand-color);
    text-decoration: none;
    margin-left: 4px;
    font-weight: 500;
    transition: all 0.2s;

    &:hover {
      color: var(--td-brand-color);
      text-decoration: underline;
    }
  }
}

.login-form-footer {
  border-bottom: none;
  padding-bottom: 8px;
  margin-top: 12px;
}

.login-features {
  margin-top: 20px;
  padding: 0;

  .feature-item {
    display: flex;
    align-items: center;
    margin-bottom: 12px;
    font-size: 13px;
    color: var(--td-text-color-secondary);
    font-family: var(--app-font-family);

    &:last-child {
      margin-bottom: 0;
    }

    .feature-icon {
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background: var(--td-success-color-light);
      color: var(--td-brand-color-active);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 12px;
      font-weight: 700;
      margin-right: 10px;
      flex-shrink: 0;
    }

    .feature-text {
      line-height: 1.4;
    }
  }
}

/* Responsive Design */
@media (max-width: 1024px) {
  .knowledge-node:nth-of-type(n + 13) {
    display: none;
  }

  .connection-line:nth-of-type(n + 13) {
    display: none;
  }

  .showcase-subtitle {
    font-size: 18px;
  }

  .header-logo {
    top: 26px;
    left: 40px;

    .logo-image {
      width: 100px;
    }
  }

  .header-links {
    top: 22px;
    right: 22px;
    gap: 8px;

    .link-text {
      display: none;
    }

    .header-link {
      padding: 10px;
      gap: 0;
    }
  }
}

@media (max-width: 768px) {
  .login-layout {
    flex-direction: column;
  }

  .knowledge-node:nth-of-type(n + 9) {
    display: none;
  }

  .connection-line:nth-of-type(n + 9) {
    display: none;
  }

  .showcase-section {
    flex: 0 0 auto;
    min-height: 50vh;
    padding: 40px 24px;
  }

  .showcase-content {
    max-width: 100%;
  }

  .header-logo {
    top: 22px;
    left: 30px;

    .logo-image {
      width: 80px;
    }
  }

  .showcase-subtitle {
    font-size: 16px;
    margin-bottom: 24px;
  }

  .feature-tags {
    margin-bottom: 24px;
  }

  .carousel-container {
    margin-top: 24px;
  }

  .form-section {
    flex: 0 0 auto;
    padding: 24px;
  }

  .header-links {
    top: 18px;
    right: 18px;
    gap: 8px;

    .link-text {
      display: inline;
    }

    .header-link {
      padding: 8px 12px;
      font-size: 12px;
    }
  }

  .form-card {
    padding: 32px 24px;
  }

  .form-title {
    font-size: 22px;
  }
}

@media (max-width: 480px) {
  .animated-bg {
    display: none;
  }

  .showcase-section {
    padding: 32px 20px;
  }

  .header-logo {
    top: 18px;
    left: 20px;

    .logo-image {
      width: 70px;
    }
  }

  .showcase-subtitle {
    font-size: 14px;
  }

  .tag {
    font-size: 12px;
    padding: 6px 16px;
  }

  .form-section {
    padding: 20px;
  }

  .header-links {
    top: 14px;
    right: 14px;
    gap: 6px;
    flex-wrap: wrap;

    .header-link {
      padding: 7px 10px;
      font-size: 11px;
    }
  }

  .form-card {
    padding: 28px 20px;
  }

  .form-header {
    margin-bottom: 24px;
  }
}

@media (prefers-reduced-motion: reduce) {

  .knowledge-node,
  .connection-line {
    animation: none !important;
    transition: none !important;
  }

  .animated-bg {
    display: none;
  }
}
</style>

<style lang="less" scoped>
/* X-Agent workspace redesign: intentionally replaces the former split-screen campaign layout. */
.workspace-login {
  --workspace-green: #07c05f;
  --workspace-green-deep: #087a49;
  --workspace-ink: #15231d;
  --workspace-muted: #66736d;
  --workspace-line: #dfe7e2;
  display: grid;
  grid-template-columns: minmax(0, 1.42fr) minmax(420px, 0.72fr);
  grid-template-rows: 78px minmax(0, 1fr);
  width: 100%;
  min-height: 100vh;
  height: auto;
  padding: 0;
  gap: 0;
  overflow-x: hidden;
  overflow-y: auto;
  color: var(--workspace-ink);
  background:
    linear-gradient(rgba(23, 52, 39, 0.035) 1px, transparent 1px),
    linear-gradient(90deg, rgba(23, 52, 39, 0.035) 1px, transparent 1px),
    #f6f8f6;
  background-size: 32px 32px;

  &::before {
    content: '';
    position: fixed;
    top: -180px;
    left: 28%;
    width: 540px;
    height: 540px;
    border-radius: 50%;
    background: radial-gradient(circle, rgba(7, 192, 95, 0.1), transparent 68%);
    pointer-events: none;
  }
}

.brand-wordmark {
  grid-column: 1;
  grid-row: 1;
  z-index: 5;
  display: inline-flex;
  align-items: center;
  align-self: center;
  justify-self: start;
  margin-left: 56px;
  color: #14231c;
  user-select: none;
}

.brand-wordmark__zh {
  font-size: 25px;
  font-weight: 760;
  letter-spacing: 0.08em;
}

.brand-wordmark__divider {
  width: 1px;
  height: 22px;
  margin: 0 13px;
  background: #bfcbc4;
}

.brand-wordmark__en {
  color: #087a49;
  font-size: 17px;
  font-weight: 760;
  letter-spacing: 0.06em;
}

.header-links {
  position: relative;
  inset: auto;
  grid-column: 2;
  grid-row: 1;
  z-index: 5;
  align-self: center;
  justify-self: end;
  margin-right: 46px;
}

.header-link,
.language-switch button {
  min-height: 36px;
  padding: 8px 12px;
  border: 1px solid #dbe4df;
  border-radius: 10px;
  background: rgba(255, 255, 255, 0.88);
  color: #405149;
  box-shadow: 0 5px 18px rgba(24, 50, 38, 0.05);
  backdrop-filter: blur(12px);

  &:hover {
    border-color: #9dcfb3;
    background: #fff;
    color: #087a49;
  }
}

.language-dropdown {
  right: 0;
  left: auto;
  border-color: #dde6e1;
  border-radius: 12px;
  box-shadow: 0 18px 42px rgba(27, 57, 43, 0.12);
}

.language-option.active {
  background: #ebf8f1;
  color: #087a49;
}

.showcase-section {
  position: relative;
  grid-column: 1;
  grid-row: 2;
  display: flex;
  min-width: 0;
  min-height: calc(100vh - 78px);
  padding: 32px 32px 46px 56px;
  overflow: visible;
  border-radius: 0;
  background: transparent;
  box-sizing: border-box;

  &::after {
    content: '';
    position: absolute;
    right: 4%;
    bottom: 5%;
    width: 180px;
    height: 180px;
    border: 1px solid rgba(7, 192, 95, 0.12);
    border-radius: 50%;
    box-shadow: 0 0 0 28px rgba(7, 192, 95, 0.025), 0 0 0 56px rgba(7, 192, 95, 0.018);
    pointer-events: none;
  }
}

.showcase-content {
  position: relative;
  z-index: 2;
  width: 100%;
  max-width: 920px;
  margin: 0;
}

.showcase-eyebrow {
  display: flex;
  align-items: center;
  gap: 9px;
  margin-bottom: 16px;
  color: #567067;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 0.16em;
  text-transform: uppercase;
}

.showcase-eyebrow__icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 25px;
  height: 25px;
  border-radius: 8px;
  background: #dcf7e8;
  color: #087a49;
  font-size: 14px;
}

.showcase-subtitle {
  max-width: 760px;
  margin: 0 0 13px;
  color: #14251d;
  font-size: clamp(38px, 3.5vw, 56px);
  font-weight: 720;
  line-height: 1.12;
  letter-spacing: -0.055em;
  text-shadow: none;
}

.showcase-description {
  max-width: 680px;
  margin: 0 0 20px;
  color: #66756e;
  font-size: 14px;
  line-height: 1.75;
}

.feature-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 26px;
}

.tag {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 7px 11px;
  border: 1px solid #dce8e1;
  border-radius: 8px;
  background: rgba(255, 255, 255, 0.72);
  color: #3e554a;
  font-size: 12px;
  font-weight: 550;
  box-shadow: 0 3px 12px rgba(32, 65, 50, 0.035);
  backdrop-filter: blur(10px);

  :deep(.t-icon) {
    color: #09a956;
    font-size: 14px;
  }
}

.feature-stage {
  position: relative;
  width: 100%;
  min-height: 330px;
  overflow: hidden;
  border: 1px solid #dce6e0;
  border-radius: 22px;
  background: rgba(255, 255, 255, 0.9);
  box-shadow: 0 24px 60px rgba(28, 60, 45, 0.1);
  backdrop-filter: blur(14px);
}

.feature-stage__rail {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  z-index: 4;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  width: 42px;
  padding: 20px 0 18px;
  border-right: 1px solid #e6ece8;
  background: #f8faf9;
}

.feature-stage__rail-label {
  color: #789087;
  font-size: 8px;
  font-weight: 700;
  letter-spacing: 0.12em;
  writing-mode: vertical-rl;
  transform: rotate(180deg);
}

.feature-stage__rail-count {
  color: #0a9050;
  font-size: 11px;
  font-weight: 750;
}

.feature-swiper {
  height: 100%;
  min-height: 330px;
  margin-left: 42px;

  :deep(.swiper-wrapper),
  :deep(.swiper-slide) {
    min-height: 330px;
  }

  :deep(.swiper-pagination) {
    right: auto;
    bottom: 18px !important;
    left: 28px;
    width: auto;
  }

  :deep(.swiper-pagination-bullet) {
    width: 20px;
    height: 3px;
    margin: 0 4px !important;
    border-radius: 99px;
    background: #b8c7bf;
    opacity: 0.55;
    transition: width 0.2s ease, background 0.2s ease;
  }

  :deep(.swiper-pagination-bullet-active) {
    width: 38px;
    background: #07c05f;
    opacity: 1;
  }
}

.feature-scene {
  display: grid;
  grid-template-columns: minmax(220px, 0.7fr) minmax(0, 1.3fr);
  min-height: 330px;
}

.feature-scene__copy {
  position: relative;
  z-index: 2;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 34px 18px 48px 34px;
  background: linear-gradient(90deg, #fff 76%, rgba(255, 255, 255, 0));

  h3 {
    margin: 14px 0 10px;
    color: #17271f;
    font-size: 22px;
    font-weight: 700;
    line-height: 1.25;
  }

  p {
    display: -webkit-box;
    max-width: 300px;
    margin: 0;
    overflow: hidden;
    color: #6b7972;
    font-size: 12px;
    line-height: 1.65;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 3;
  }
}

.feature-scene__index {
  color: #07a953;
  font-size: 12px;
  font-weight: 800;
  letter-spacing: 0.14em;
}

.feature-scene__signal {
  display: flex;
  gap: 4px;
  margin-top: 20px;

  span {
    width: 4px;
    height: 4px;
    border-radius: 50%;
    background: #08b75a;

    &:nth-child(2) {
      opacity: 0.55;
    }

    &:nth-child(3) {
      opacity: 0.25;
    }
  }
}

.feature-scene__visual {
  position: relative;
  min-width: 0;
  min-height: 330px;
  overflow: hidden;
  background: #f4f8f5;

  &::after {
    content: '';
    position: absolute;
    inset: 0;
    box-shadow: inset 28px 0 38px rgba(255, 255, 255, 0.85);
    pointer-events: none;
  }
}

.slide-image {
  width: 100%;
  height: 100%;
  min-height: 330px;
  object-fit: cover;
  object-position: center;
  transform: scale(1.015);
}

.form-section {
  position: relative;
  grid-column: 2;
  grid-row: 2;
  display: flex;
  align-items: center;
  min-width: 0;
  min-height: calc(100vh - 78px);
  padding: 32px 54px 58px;
  border-left: 1px solid rgba(207, 220, 213, 0.7);
  background:
    radial-gradient(circle at 78% 12%, rgba(7, 192, 95, 0.08), transparent 28%),
    rgba(239, 243, 240, 0.82);
  box-sizing: border-box;

  &::before {
    content: 'ACCESS / X-AGENT';
    position: absolute;
    right: 22px;
    bottom: 22px;
    color: rgba(42, 78, 61, 0.24);
    font-size: 9px;
    font-weight: 750;
    letter-spacing: 0.18em;
  }
}

.form-panel {
  width: 100%;
  max-width: 430px;
  margin: 0 auto;
}

.form-card {
  width: 100%;
  padding: 34px;
  border: 1px solid #dbe5df;
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.96);
  box-shadow: 0 22px 54px rgba(28, 58, 44, 0.1);
  box-sizing: border-box;
}

.form-header {
  margin-bottom: 25px;
  text-align: left;
}

.form-title {
  margin-bottom: 8px;
  color: #16271e;
  font-size: 27px;
  font-weight: 720;
  letter-spacing: -0.03em;
}

.form-welcome,
.form-subtitle {
  color: #738078;
  font-size: 12px;
  line-height: 1.65;
}

.form-hint {
  margin-top: 13px;
  padding: 9px 11px;
  border: 1px solid #d8eee2;
  border-radius: 9px;
  background: #f0faf4;
  color: #26704d;
  font-size: 11px;
}

.form-content {
  :deep(.t-form-item__label) {
    margin-bottom: 6px;
    color: #42534a;
    font-size: 12px;
    font-weight: 620;
  }

  :deep(.t-form-item) {
    margin-bottom: 16px;
  }

  :deep(.t-input) {
    min-height: 44px;
    border-color: #dbe4df;
    border-radius: 9px;
    background: #fbfcfb;

    &:hover {
      border-color: #8fc6a8;
    }

    &:focus-within {
      border-color: #08a955;
      box-shadow: 0 0 0 3px rgba(7, 192, 95, 0.1);
    }
  }
}

.submit-button {
  height: 44px;
  margin: 17px 0 15px;
  border-color: #08a955;
  border-radius: 9px;
  background: linear-gradient(105deg, #08a955, #07c05f);
  box-shadow: 0 10px 22px rgba(7, 192, 95, 0.2);

  &:hover {
    border-color: #078e49;
    background: linear-gradient(105deg, #078e49, #08ac55);
  }
}

.register-cta__button,
.oidc-button {
  height: 44px;
  border-radius: 9px;
}

.register-cta__button {
  border-color: #b9cbc1;
  color: #286246;

  &:hover {
    border-color: #72ad8c;
    background: #f2faf5;
    color: #087a49;
  }
}

.register-cta__divider span,
.oidc-divider span {
  background: #fff;
}

.login-features {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 7px;
  margin-top: 20px;
  padding-top: 17px;
  border-top: 1px solid #e8eeea;

  .feature-item {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 5px;
    margin: 0;
    color: #748079;
    font-size: 9px;
    line-height: 1.35;

    .feature-icon {
      width: 17px;
      height: 17px;
      margin: 0;
      background: #e7f7ee;
      color: #08a955;
      font-size: 9px;
    }
  }
}

@media (max-width: 1180px) {
  .workspace-login {
    grid-template-columns: minmax(0, 1.16fr) minmax(390px, 0.84fr);
  }

  .brand-wordmark {
    margin-left: 36px;
  }

  .showcase-section {
    padding-right: 24px;
    padding-left: 36px;
  }

  .showcase-subtitle {
    font-size: 40px;
  }

  .feature-scene {
    grid-template-columns: minmax(195px, 0.72fr) minmax(0, 1.28fr);
  }

  .form-section {
    padding-right: 32px;
    padding-left: 32px;
  }
}

@media (max-width: 900px) {
  .workspace-login {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 66px auto auto;
    min-height: 100vh;
  }

  .brand-wordmark {
    grid-column: 1;
    grid-row: 1;
    margin-left: 24px;
  }

  .brand-wordmark__zh {
    font-size: 21px;
  }

  .brand-wordmark__en {
    font-size: 15px;
  }

  .header-links {
    grid-column: 1;
    grid-row: 1;
    margin-right: 20px;
  }

  .showcase-section {
    grid-column: 1;
    grid-row: 2;
    min-height: auto;
    padding: 28px 20px 30px;

    &::after {
      display: none;
    }
  }

  .showcase-content {
    max-width: none;
  }

  .showcase-subtitle {
    max-width: 680px;
    font-size: 36px;
  }

  .feature-stage {
    min-height: 285px;
  }

  .feature-swiper,
  .feature-swiper :deep(.swiper-wrapper),
  .feature-swiper :deep(.swiper-slide) {
    min-height: 285px;
  }

  .feature-scene {
    min-height: 285px;
  }

  .feature-scene__visual,
  .slide-image {
    min-height: 285px;
  }

  .form-section {
    grid-column: 1;
    grid-row: 3;
    min-height: auto;
    padding: 38px 20px 64px;
    border-top: 1px solid #dbe5df;
    border-left: 0;
  }
}

@media (max-width: 560px) {
  .workspace-login {
    grid-template-rows: 60px auto auto;
  }

  .brand-wordmark {
    margin-left: 18px;
  }

  .brand-wordmark__zh {
    font-size: 18px;
  }

  .brand-wordmark__divider {
    height: 18px;
    margin: 0 9px;
  }

  .brand-wordmark__en {
    font-size: 13px;
  }

  .header-links {
    margin-right: 14px;
  }

  .language-switch button {
    min-height: 32px;
    padding: 6px 8px;

    .lang-flag-icon {
      display: none;
    }
  }

  .showcase-section {
    padding: 22px 14px 24px;
  }

  .showcase-eyebrow {
    margin-bottom: 12px;
    font-size: 9px;
  }

  .showcase-subtitle {
    margin-bottom: 11px;
    font-size: 30px;
    line-height: 1.16;
  }

  .showcase-description {
    display: block;
    margin-bottom: 15px;
    font-size: 12px;
    line-height: 1.55;
  }

  .feature-tags {
    gap: 6px;
    margin-bottom: 18px;
  }

  .tag {
    padding: 5px 7px;
    font-size: 9px;
  }

  .feature-stage {
    min-height: 350px;
    border-radius: 16px;
  }

  .feature-stage__rail {
    display: none;
  }

  .feature-swiper {
    min-height: 350px;
    margin-left: 0;

    :deep(.swiper-wrapper),
    :deep(.swiper-slide) {
      min-height: 350px;
    }

    :deep(.swiper-pagination) {
      bottom: 15px !important;
      left: 20px;
    }
  }

  .feature-scene {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 142px 208px;
    min-height: 350px;
  }

  .feature-scene__copy {
    grid-row: 1;
    padding: 20px 20px 28px;
    background: #fff;

    h3 {
      margin: 7px 0 5px;
      font-size: 17px;
    }

    p {
      max-width: none;
      font-size: 10px;
      -webkit-line-clamp: 2;
    }
  }

  .feature-scene__signal {
    display: none;
  }

  .feature-scene__visual,
  .slide-image {
    min-height: 208px;
    height: 208px;
  }

  .feature-scene__visual {
    grid-row: 2;

    &::after {
      box-shadow: inset 0 18px 26px rgba(255, 255, 255, 0.68);
    }
  }

  .form-section {
    padding: 28px 14px 48px;
  }

  .form-card {
    padding: 26px 21px;
    border-radius: 17px;
  }

  .login-features {
    grid-template-columns: 1fr;

    .feature-item {
      flex-direction: row;
      align-items: center;
      gap: 7px;
      font-size: 10px;
    }
  }
}
</style>

<style lang="less">
html[theme-mode="dark"] {
  .workspace-login {
    --workspace-ink: #ecf5f0;
    --workspace-muted: #99aaa1;
    --workspace-line: #2b3c33;
    background:
      linear-gradient(rgba(194, 232, 211, 0.035) 1px, transparent 1px),
      linear-gradient(90deg, rgba(194, 232, 211, 0.035) 1px, transparent 1px),
      #111914;
    background-size: 32px 32px;
  }

  .brand-wordmark,
  .showcase-subtitle,
  .form-title {
    color: #edf6f1;
  }

  .showcase-description,
  .form-welcome,
  .form-subtitle {
    color: #98aaa0;
  }

  .tag,
  .feature-stage,
  .form-card {
    border-color: #304139;
    background: rgba(24, 35, 29, 0.96);
  }

  .feature-stage__rail,
  .feature-scene__copy {
    border-color: #304139;
    background: #19251f;
  }

  .feature-scene__copy h3 {
    color: #edf6f1;
  }

  .feature-scene__visual {
    background: #eaf3ed;
  }

  .form-section {
    border-color: #2b3d34;
    background: rgba(20, 30, 25, 0.88);
  }

  .register-cta__divider span,
  .oidc-divider span {
    background: #18231d;
  }
}
</style>

<style lang="less" scoped>
/* 智川 X-Agent 品牌主题：深蓝智能中枢 + 电光青视觉语言。 */
.login-layout {
  background: #f2f5fb;
}

.showcase-section {
  background:
    radial-gradient(circle at 18% 16%, rgba(74, 211, 248, 0.28), transparent 27%),
    radial-gradient(circle at 88% 78%, rgba(45, 78, 246, 0.34), transparent 34%),
    linear-gradient(145deg, #111f55 0%, #0a153b 52%, #07112f 100%);

  &::after {
    border-color: rgba(78, 214, 249, 0.14);
    box-shadow:
      0 0 0 64px rgba(47, 82, 246, 0.06),
      0 0 0 128px rgba(78, 214, 249, 0.035);
  }
}

.knowledge-node {
  background: rgba(68, 210, 247, 0.1);
  border-color: rgba(99, 222, 252, 0.32);
  box-shadow:
    0 0 0 7px rgba(64, 205, 246, 0.04),
    0 0 24px rgba(55, 100, 255, 0.22);
}

.node-icon {
  color: rgba(136, 230, 255, 0.82);
}

.connection-line {
  stroke: rgba(76, 208, 247, 0.5);
}

.showcase-eyebrow {
  color: rgba(169, 225, 255, 0.78);
}

.showcase-eyebrow__dot {
  background: #4bd5f7;
  box-shadow: 0 0 0 5px rgba(75, 213, 247, 0.14), 0 0 18px rgba(75, 213, 247, 0.55);
}

.showcase-subtitle {
  color: #f7f9ff;
  text-shadow: 0 8px 36px rgba(27, 59, 190, 0.22);
}

.showcase-description {
  color: rgba(211, 224, 255, 0.7);
}

.tag {
  border-color: rgba(110, 204, 255, 0.2);
  background: linear-gradient(135deg, rgba(59, 91, 235, 0.18), rgba(67, 207, 246, 0.09));
  color: rgba(231, 241, 255, 0.88);
}

.carousel-container {
  border-color: rgba(92, 204, 255, 0.24);
  background: linear-gradient(145deg, rgba(52, 84, 224, 0.14), rgba(76, 214, 249, 0.07));
  box-shadow: 0 28px 78px rgba(1, 8, 39, 0.3);
}

.screenshot-swiper {
  box-shadow: 0 26px 64px rgba(1, 8, 39, 0.28);

  :deep(.swiper-pagination-bullet-active) {
    background: #4bd5f7;
  }
}

.header-logo {
  display: flex;
  align-items: center;
  padding: 8px 12px;
  border: 1px solid rgba(255, 255, 255, 0.42);
  border-radius: 14px;
  background: rgba(255, 255, 255, 0.94);
  box-shadow: 0 12px 36px rgba(3, 12, 51, 0.18);
  backdrop-filter: blur(14px);

  .logo-image {
    width: 150px;
    filter: none;
    opacity: 1;
  }
}

.header-link,
.language-switch button {
  border-color: #dbe2f3;
  background: rgba(255, 255, 255, 0.9);
  color: #263a74;
  box-shadow: 0 8px 24px rgba(39, 61, 128, 0.08);

  &:hover {
    border-color: #aec3f5;
    background: #fff;
    color: #2449dc;
  }
}

.language-option.active {
  background: #edf2ff;
  color: #2449dc;
}

.form-card {
  border-color: #dfe5f2;
  background: rgba(255, 255, 255, 0.97);
  box-shadow:
    0 26px 76px rgba(41, 61, 120, 0.12),
    0 3px 10px rgba(30, 48, 103, 0.05);
}

.form-title {
  color: #15254f;
}

.form-welcome,
.form-subtitle {
  color: #7180a5;
}

.form-hint {
  border-color: #d9e5ff;
  background: #f0f5ff;
  color: #3155c7;
}

.form-content {
  :deep(.t-form-item__label) {
    color: #34466e;
  }

  :deep(.t-input) {
    border-color: #dce3f1;
    background: #fbfcff;

    &:hover {
      border-color: #8faaf1;
    }

    &:focus-within {
      border-color: #3158f5;
      box-shadow: 0 0 0 3px rgba(49, 88, 245, 0.11);
    }
  }
}

.submit-button {
  border-color: #294ff0;
  background: linear-gradient(100deg, #284cf0 0%, #315ff6 54%, #278fdc 100%);
  box-shadow: 0 12px 28px rgba(43, 79, 237, 0.25);

  &:hover {
    border-color: #2243d8;
    background: linear-gradient(100deg, #2345dc 0%, #2b54e5 54%, #2382cc 100%);
  }
}

.register-cta__button {
  border-color: #afbfeb;
  color: #2e52d6;

  &:hover {
    border-color: #6f8ce5;
    background: #f0f4ff;
    color: #2446c8;
  }
}

.login-features {
  border-top-color: #e9edf6;

  .feature-item {
    color: #69799d;

    .feature-icon {
      background: #eaf0ff;
      color: #3158f5;
    }
  }
}

@media (max-width: 900px) {
  .showcase-section {
    background:
      radial-gradient(circle at 18% 16%, rgba(74, 211, 248, 0.26), transparent 28%),
      linear-gradient(145deg, #13255f 0%, #0a153b 60%, #081130 100%);
  }

  .header-link,
  .language-switch button {
    border-color: rgba(132, 218, 255, 0.28);
    background: rgba(30, 52, 126, 0.38);
    color: #e9f5ff;
  }
}

@media (max-width: 560px) {
  .header-logo {
    padding: 6px 9px;
    border-radius: 11px;

    .logo-image {
      width: 112px;
    }
  }
}
</style>

<style lang="less">
html[theme-mode="dark"] {
  .login-layout {
    background: #0b1020;
  }

  .showcase-section {
    background:
      radial-gradient(circle at 18% 16%, rgba(74, 211, 248, 0.2), transparent 27%),
      linear-gradient(145deg, #111f55 0%, #091538 54%, #060e29 100%);
  }

  .form-card {
    border-color: #293557;
    background: #131a2d !important;
  }

  .form-title {
    color: #f3f6ff;
  }

  .form-welcome,
  .form-subtitle,
  .login-features .feature-item {
    color: #93a3c7;
  }

  .form-content .t-input {
    border-color: #34415f !important;
    background: #0d1426 !important;
  }

  .register-cta__divider span,
  .oidc-divider span {
    background: #131a2d;
  }

  .login-features {
    border-top-color: #29344e;
  }
}
</style>

<style lang="less" scoped>
/* 2026 login refresh: quiet enterprise surfaces with a focused brand stage. */
.login-layout {
  height: 100vh;
  min-height: 100vh;
  padding: 18px;
  gap: 18px;
  box-sizing: border-box;
  overflow-x: hidden;
  overflow-y: auto;
  background: #f3f6f4;

  &::before {
    display: none;
  }
}

.animated-bg {
  top: 18px;
  right: auto;
  bottom: 18px;
  left: 18px;
  width: calc(58% - 27px);
  border-radius: 28px;
  z-index: 1;
  opacity: 0.72;
}

.knowledge-node {
  width: 34px;
  height: 34px;
  border-width: 1px;
  background: rgba(210, 255, 235, 0.08);
  border-color: rgba(210, 255, 235, 0.22);
  box-shadow: 0 0 0 7px rgba(210, 255, 235, 0.025);
  animation-duration: 8s;
}

.node-icon {
  width: 16px;
  height: 16px;
  color: rgba(221, 255, 241, 0.7);
}

.knowledge-lines {
  opacity: 0.24;
}

.connection-line {
  stroke: rgba(194, 247, 224, 0.42);
  stroke-width: 0.8;
  stroke-dasharray: 2, 4;
  animation-duration: 16s;
}

.showcase-section {
  flex: 0 0 58%;
  min-height: calc(100vh - 36px);
  align-items: center;
  padding: 116px 64px 54px;
  border-radius: 28px;
  overflow: hidden;
  background:
    radial-gradient(circle at 14% 18%, rgba(95, 220, 169, 0.2), transparent 28%),
    radial-gradient(circle at 92% 90%, rgba(56, 178, 140, 0.15), transparent 32%),
    linear-gradient(145deg, #123f36 0%, #082f29 54%, #06251f 100%);

  &::after {
    content: '';
    position: absolute;
    right: -120px;
    bottom: -120px;
    width: 420px;
    height: 420px;
    border: 1px solid rgba(201, 255, 231, 0.08);
    border-radius: 50%;
    box-shadow:
      0 0 0 64px rgba(201, 255, 231, 0.025),
      0 0 0 128px rgba(201, 255, 231, 0.018);
    pointer-events: none;
  }
}

.showcase-content {
  max-width: 680px;
  margin: 0;
}

.showcase-eyebrow {
  display: flex;
  align-items: center;
  gap: 9px;
  margin-bottom: 20px;
  color: rgba(222, 255, 241, 0.68);
  font-size: 12px;
  font-weight: 650;
  letter-spacing: 1.8px;
  text-transform: uppercase;
}

.showcase-eyebrow__dot {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #67dda9;
  box-shadow: 0 0 0 5px rgba(103, 221, 169, 0.12);
}

.showcase-subtitle {
  max-width: 11em;
  margin: 0 0 18px;
  color: #f4fff9;
  font-size: clamp(38px, 3.7vw, 58px);
  font-weight: 650;
  line-height: 1.12;
  letter-spacing: -1.8px;
}

.showcase-description {
  max-width: 540px;
  margin-bottom: 26px;
  color: rgba(231, 255, 244, 0.66);
  font-size: 15px;
  line-height: 1.8;
}

.feature-tags {
  gap: 9px;
  margin-bottom: 0;
}

.tag {
  padding: 7px 13px;
  border: 1px solid rgba(207, 255, 233, 0.13);
  border-radius: 9px;
  background: rgba(207, 255, 233, 0.07);
  color: rgba(241, 255, 248, 0.78);
  font-size: 12px;
  font-weight: 500;
  backdrop-filter: blur(10px);
}

.carousel-container {
  width: min(100%, 520px);
  margin-top: 34px;
  padding: 7px;
  border: 1px solid rgba(219, 255, 238, 0.13);
  border-radius: 19px;
  background: rgba(225, 255, 241, 0.065);
  box-sizing: border-box;
  backdrop-filter: blur(14px);
}

.screenshot-swiper {
  border-radius: 13px;
  padding-bottom: 26px;
  box-shadow: 0 30px 70px rgba(0, 17, 13, 0.28);

  :deep(.swiper-pagination) {
    bottom: 7px !important;
  }

  :deep(.swiper-pagination-bullet) {
    width: 5px;
    height: 5px;
    margin: 0 4px !important;
    background: rgba(222, 255, 240, 0.35);
  }

  :deep(.swiper-pagination-bullet-active) {
    width: 18px;
    background: #80e4b8;
  }
}

.slide-content {
  border-radius: 11px;
  background: #eaf5f0;
}

.header-logo {
  top: 44px;
  left: 54px;
  cursor: default;

  .logo-image {
    width: 128px;
    filter: brightness(0) invert(1);
    opacity: 0.92;
  }
}

.header-links {
  position: absolute;
  top: 34px;
  right: 34px;
}

.header-link,
.language-switch button {
  min-height: 38px;
  padding: 9px 13px;
  border: 1px solid #dce5e1;
  border-radius: 11px;
  background: rgba(255, 255, 255, 0.82);
  color: #31534a;
  box-shadow: 0 6px 22px rgba(35, 72, 60, 0.06);
  backdrop-filter: blur(12px);

  &:hover {
    border-color: #b8cec5;
    background: #fff;
    color: #153f35;
  }
}

.language-dropdown {
  top: calc(100% + 10px);
  min-width: 172px;
  padding: 6px;
  border-color: #e1e8e5;
  border-radius: 13px;
  background: rgba(255, 255, 255, 0.98);
  box-shadow: 0 18px 50px rgba(25, 60, 49, 0.15);
}

.language-option {
  border-radius: 8px;

  &.active {
    background: #eaf7f1;
    color: #0a7459;
  }
}

.form-section {
  flex: 0 0 calc(42% - 18px);
  min-width: 0;
  min-height: calc(100vh - 36px);
  align-items: center;
  padding: 92px 48px 48px;
}

.form-panel {
  max-width: 440px;
  margin: 0;
}

.form-card {
  padding: 38px;
  border: 1px solid #e0e8e4;
  border-radius: 24px;
  background: rgba(255, 255, 255, 0.96);
  box-shadow:
    0 24px 70px rgba(31, 64, 53, 0.09),
    0 2px 8px rgba(31, 64, 53, 0.04);
}

.form-header {
  margin-bottom: 28px;
  text-align: left;
}

.form-title {
  margin-bottom: 9px;
  color: #173c33;
  font-size: 28px;
  font-weight: 650;
  letter-spacing: -0.6px;
}

.form-welcome,
.form-subtitle {
  color: #71857d;
  line-height: 1.55;
}

.form-hint {
  margin-top: 14px;
  padding: 10px 12px;
  border: 1px solid #dcefe6;
  border-radius: 10px;
  background: #f1faf6;
  color: #28735d;
  text-align: center;
}

.form-content {
  :deep(.t-form-item__label) {
    margin-bottom: 7px;
    color: #315148;
    font-size: 13px;
    font-weight: 600;
  }

  :deep(.t-input) {
    min-height: 45px;
    border-color: #dce5e1;
    border-radius: 11px;
    background: #fbfcfb;

    &:hover {
      border-color: #8fb9a9;
    }

    &:focus-within {
      border-color: #238568;
      box-shadow: 0 0 0 3px rgba(35, 133, 104, 0.11);
    }
  }

  :deep(.t-form-item) {
    margin-bottom: 17px;
  }
}

.submit-button,
.oidc-button,
.register-cta__button {
  height: 45px;
  border-radius: 11px;
}

.submit-button {
  margin: 18px 0 16px;
  border-color: #0b795f;
  background: #0b795f;
  box-shadow: 0 10px 24px rgba(11, 121, 95, 0.18);

  &:hover {
    border-color: #096a53;
    background: #096a53;
  }
}

.register-cta__divider span,
.oidc-divider span {
  background: #fff;
}

.register-cta__button {
  border-color: #a7c5ba;
  color: #176b55;

  &:hover {
    border-color: #4c9b82;
    background: #f1faf6;
    color: #0d624d;
  }
}

.login-features {
  display: grid;
  grid-template-columns: 1fr;
  gap: 9px;
  margin-top: 22px;
  padding-top: 20px;
  border-top: 1px solid #edf1ef;

  .feature-item {
    margin: 0;
    color: #647a71;
    font-size: 12px;

    .feature-icon {
      width: 18px;
      height: 18px;
      margin-right: 9px;
      background: #e6f6ef;
      color: #15805f;
      font-size: 10px;
    }
  }
}

@media (max-width: 1180px) {
  .showcase-section {
    flex-basis: 54%;
    padding-right: 44px;
    padding-left: 44px;
  }

  .animated-bg {
    width: calc(54% - 27px);
  }

  .showcase-subtitle {
    font-size: 38px;
  }

  .form-section {
    flex-basis: calc(46% - 18px);
    padding-right: 30px;
    padding-left: 30px;
  }
}

@media (max-width: 900px) {
  .login-layout {
    display: block;
    height: auto;
    padding: 0;
  }

  .animated-bg {
    top: 0;
    left: 0;
    width: 100%;
    height: 310px;
    border-radius: 0 0 28px 28px;
  }

  .showcase-section {
    min-height: 310px;
    padding: 86px 32px 34px;
    border-radius: 0 0 28px 28px;
  }

  .showcase-content {
    max-width: 620px;
  }

  .showcase-eyebrow {
    margin-bottom: 14px;
  }

  .showcase-subtitle {
    max-width: 16em;
    margin-bottom: 12px;
    font-size: 32px;
    letter-spacing: -1px;
  }

  .showcase-description {
    margin-bottom: 18px;
    line-height: 1.55;
  }

  .carousel-container {
    display: none;
  }

  .header-logo {
    top: 28px;
    left: 32px;

    .logo-image {
      width: 110px;
    }
  }

  .header-links {
    top: 22px;
    right: 22px;

    .link-text {
      display: inline;
    }
  }

  .header-link,
  .language-switch button {
    border-color: rgba(226, 255, 242, 0.18);
    background: rgba(231, 255, 244, 0.1);
    color: rgba(245, 255, 250, 0.88);
    box-shadow: none;

    &:hover {
      border-color: rgba(226, 255, 242, 0.3);
      background: rgba(231, 255, 244, 0.17);
      color: #fff;
    }
  }

  .form-section {
    min-height: auto;
    padding: 42px 20px 64px;
  }

  .form-panel {
    max-width: 480px;
  }
}

@media (max-width: 560px) {
  .animated-bg {
    display: block;
    height: 240px;
  }

  .knowledge-node:nth-of-type(n + 6),
  .connection-line:nth-of-type(n + 6) {
    display: none;
  }

  .showcase-section {
    min-height: 240px;
    padding: 76px 22px 24px;
  }

  .showcase-eyebrow {
    font-size: 10px;
  }

  .showcase-subtitle {
    margin-bottom: 16px;
    font-size: 27px;
    line-height: 1.2;
  }

  .showcase-description {
    display: none;
  }

  .feature-tags {
    gap: 6px;
  }

  .tag {
    padding: 5px 8px;
    font-size: 10px;
  }

  .header-logo {
    top: 24px;
    left: 22px;

    .logo-image {
      width: 92px;
    }
  }

  .header-links {
    top: 16px;
    right: 14px;
  }

  .header-link,
  .language-switch button {
    min-height: 34px;
    padding: 7px 9px;

    .link-text {
      display: none;
    }
  }

  .form-section {
    padding: 28px 14px 42px;
  }

  .form-card {
    padding: 28px 22px;
    border-radius: 20px;
  }

  .form-title {
    font-size: 25px;
  }
}
</style>

<style lang="less">
html[theme-mode="dark"] {
  .login-layout {
    background: #101916;
  }

  .showcase-section {
    background:
      radial-gradient(circle at 14% 18%, rgba(95, 220, 169, 0.16), transparent 28%),
      linear-gradient(145deg, #123c34 0%, #082d27 54%, #061f1b 100%);
  }

  .form-card {
    border-color: #2a3934;
    background: #17221e !important;
    box-shadow: 0 24px 70px rgba(0, 0, 0, 0.28) !important;
  }

  .form-title {
    color: #eff8f4;
  }

  .form-welcome,
  .form-subtitle,
  .login-features .feature-item {
    color: #95a9a1;
  }

  .form-content .t-input {
    border-color: #33463f !important;
    background: #101915 !important;
  }

  .register-cta__divider span,
  .oidc-divider span {
    background: #17221e;
  }

  .login-features {
    border-top-color: #293832;
  }

  .header-link,
  .language-switch button {
    border-color: #33443e;
    background: rgba(23, 34, 30, 0.88);
    color: #c5d7d0;
  }
}
</style>

<style lang="less">
html[theme-mode="dark"] {
  .login-layout {
    background: #101916;
  }

  .knowledge-node {
    background: rgba(255, 255, 255, 0.1);
    border-color: rgba(255, 255, 255, 0.2);
    box-shadow: 0 0 8px rgba(255, 255, 255, 0.15);
  }

  .connection-line {
    stroke: rgba(255, 255, 255, 0.25);
  }

  .header-logo .logo-image {
    filter: invert(1) hue-rotate(180deg) brightness(1.1);
  }

  .header-link {
    background: rgba(255, 255, 255, 0.12);
    border-color: rgba(255, 255, 255, 0.15);

    &:hover {
      background: rgba(255, 255, 255, 0.2);
    }
  }

  .language-switch button {
    background: rgba(255, 255, 255, 0.12);
    border-color: rgba(255, 255, 255, 0.15);

    &:hover {
      background: rgba(255, 255, 255, 0.2);
    }
  }

  .language-dropdown {
    background: rgba(36, 36, 36, 0.97) !important;
    border-color: var(--td-component-stroke) !important;
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.4) !important;
  }

  .tag {
    background: rgba(255, 255, 255, 0.12);
  }

  .form-card {
    border-color: #2a3934;
    background: #17221e !important;
    box-shadow: 0 24px 70px rgba(0, 0, 0, 0.28) !important;
  }

  .register-cta__divider span {
    background: #17221e;
  }

  .form-content .t-input {
    background: #101915 !important;
    border-color: #33463f !important;

    &:hover {
      border-color: var(--td-brand-color) !important;
    }

    &:focus-within {
      border-color: var(--td-brand-color) !important;
    }
  }

  .screenshot-swiper .swiper-pagination-bullet-active {
    background: rgba(255, 255, 255, 0.9) !important;
  }

  .login-features .feature-icon {
    background: rgba(6, 176, 77, 0.15);
  }
}
</style>

<style lang="less" scoped>
/* Final X-Agent palette override. Kept last so the responsive layout above remains intact. */
.login-layout {
  background: #f2f5fb;
}

.showcase-section {
  background:
    radial-gradient(circle at 18% 16%, rgba(74, 211, 248, 0.28), transparent 27%),
    radial-gradient(circle at 88% 78%, rgba(45, 78, 246, 0.34), transparent 34%),
    linear-gradient(145deg, #111f55 0%, #0a153b 52%, #07112f 100%);

  &::after {
    border-color: rgba(78, 214, 249, 0.14);
    box-shadow:
      0 0 0 64px rgba(47, 82, 246, 0.06),
      0 0 0 128px rgba(78, 214, 249, 0.035);
  }
}

.knowledge-node {
  background: rgba(68, 210, 247, 0.1);
  border-color: rgba(99, 222, 252, 0.32);
  box-shadow: 0 0 0 7px rgba(64, 205, 246, 0.04), 0 0 24px rgba(55, 100, 255, 0.22);
}

.node-icon,
.showcase-eyebrow {
  color: rgba(169, 225, 255, 0.78);
}

.connection-line {
  stroke: rgba(76, 208, 247, 0.5);
}

.showcase-eyebrow__dot {
  background: #4bd5f7;
  box-shadow: 0 0 0 5px rgba(75, 213, 247, 0.14), 0 0 18px rgba(75, 213, 247, 0.55);
}

.showcase-description {
  color: rgba(211, 224, 255, 0.7);
}

.tag {
  border-color: rgba(110, 204, 255, 0.2);
  background: linear-gradient(135deg, rgba(59, 91, 235, 0.18), rgba(67, 207, 246, 0.09));
  color: rgba(231, 241, 255, 0.88);
}

.carousel-container {
  border-color: rgba(92, 204, 255, 0.24);
  background: linear-gradient(145deg, rgba(52, 84, 224, 0.14), rgba(76, 214, 249, 0.07));
}

.screenshot-swiper :deep(.swiper-pagination-bullet-active) {
  background: #4bd5f7;
}

.header-logo {
  display: flex;
  align-items: center;
  padding: 8px 12px;
  border: 1px solid rgba(255, 255, 255, 0.42);
  border-radius: 14px;
  background: rgba(255, 255, 255, 0.94);
  box-shadow: 0 12px 36px rgba(3, 12, 51, 0.18);

  .logo-image {
    width: 150px;
    filter: none;
    opacity: 1;
  }
}

.language-switch button {
  border-color: #dbe2f3;
  background: rgba(255, 255, 255, 0.9);
  color: #263a74;
}

.language-option.active {
  background: #edf2ff;
  color: #2449dc;
}

.form-card {
  border-color: #dfe5f2;
  box-shadow: 0 26px 76px rgba(41, 61, 120, 0.12), 0 3px 10px rgba(30, 48, 103, 0.05);
}

.form-title {
  color: #15254f;
}

.form-welcome,
.form-subtitle {
  color: #7180a5;
}

.form-hint {
  border-color: #d9e5ff;
  background: #f0f5ff;
  color: #3155c7;
}

.form-content {
  :deep(.t-form-item__label) {
    color: #34466e;
  }

  :deep(.t-input) {
    border-color: #dce3f1;
    background: #fbfcff;

    &:hover {
      border-color: #8faaf1;
    }

    &:focus-within {
      border-color: #3158f5;
      box-shadow: 0 0 0 3px rgba(49, 88, 245, 0.11);
    }
  }
}

.submit-button {
  border-color: #294ff0;
  background: linear-gradient(100deg, #284cf0 0%, #315ff6 54%, #278fdc 100%);
  box-shadow: 0 12px 28px rgba(43, 79, 237, 0.25);

  &:hover {
    border-color: #2243d8;
    background: linear-gradient(100deg, #2345dc 0%, #2b54e5 54%, #2382cc 100%);
  }
}

.register-cta__button {
  border-color: #afbfeb;
  color: #2e52d6;

  &:hover {
    border-color: #6f8ce5;
    background: #f0f4ff;
    color: #2446c8;
  }
}

.login-features {
  border-top-color: #e9edf6;

  .feature-item {
    color: #69799d;

    .feature-icon {
      background: #eaf0ff;
      color: #3158f5;
    }
  }
}

@media (max-width: 900px) {
  .header-logo .logo-image {
    width: 128px;
  }

  .language-switch button {
    border-color: rgba(132, 218, 255, 0.28);
    background: rgba(30, 52, 126, 0.38);
    color: #e9f5ff;
  }
}

@media (max-width: 560px) {
  .header-logo {
    padding: 6px 9px;
    border-radius: 11px;

    .logo-image {
      width: 104px;
    }
  }
}
</style>

<style lang="less">
html[theme-mode="dark"] {
  .login-layout {
    background: #0b1020;
  }

  .showcase-section {
    background:
      radial-gradient(circle at 18% 16%, rgba(74, 211, 248, 0.22), transparent 28%),
      linear-gradient(145deg, #101e52 0%, #091438 58%, #060e28 100%);
  }

  .header-logo .logo-image {
    filter: none;
  }

  .form-card {
    border-color: #28344f;
    background: #151c30 !important;
  }

  .form-content .t-input {
    border-color: #34405d !important;
    background: #0e1425 !important;
  }

  .register-cta__divider span,
  .oidc-divider span {
    background: #151c30;
  }

  .login-features {
    border-top-color: #29344e;
  }

  .login-features .feature-icon {
    background: rgba(49, 88, 245, 0.18);
  }
}
</style>

<style lang="less" scoped>
/* Final login composition: one viewport, one visual language, no legacy height stacking. */
.workspace-login.workspace-login {
  position: relative;
  display: grid;
  grid-template-columns: minmax(0, 1.44fr) minmax(390px, 0.72fr);
  grid-template-rows: 58px minmax(0, 1fr);
  width: 100%;
  height: 100vh;
  min-height: 0;
  padding: 14px;
  gap: 12px;
  overflow: hidden;
  background:
    radial-gradient(circle at 12% 4%, rgba(54, 225, 166, 0.2), transparent 28%),
    radial-gradient(circle at 88% 10%, rgba(73, 139, 255, 0.18), transparent 27%),
    linear-gradient(135deg, #f1fbf6 0%, #eef5ff 52%, #f7fbf9 100%);
  background-size: auto;

  &::before {
    display: block;
    content: '';
    position: absolute;
    inset: 0;
    background:
      linear-gradient(rgba(20, 94, 69, 0.035) 1px, transparent 1px),
      linear-gradient(90deg, rgba(20, 94, 69, 0.035) 1px, transparent 1px);
    background-size: 34px 34px;
    mask-image: linear-gradient(115deg, rgba(0, 0, 0, 0.76), transparent 78%);
    pointer-events: none;
  }
}

.workspace-login .brand-wordmark {
  grid-column: 1;
  grid-row: 1;
  margin-left: 24px;
}

.workspace-login .brand-wordmark__zh {
  font-size: 23px;
}

.workspace-login .brand-wordmark__en {
  color: #087a5b;
  font-size: 16px;
}

.workspace-login .header-links {
  grid-column: 2;
  grid-row: 1;
  margin-right: 18px;
}

.workspace-login .language-switch button {
  min-height: 34px;
  padding: 7px 11px;
  border-color: rgba(148, 182, 172, 0.38);
  background: rgba(255, 255, 255, 0.68);
  color: #315f52;
  box-shadow: 0 8px 24px rgba(30, 77, 61, 0.07);
  backdrop-filter: blur(18px);
}

.workspace-login .showcase-section {
  position: relative;
  grid-column: 1;
  grid-row: 2;
  min-width: 0;
  min-height: 0;
  height: auto;
  padding: 22px 28px 24px;
  overflow: hidden;
  border: 1px solid rgba(255, 255, 255, 0.8);
  border-radius: 28px;
  background:
    radial-gradient(circle at 2% 2%, rgba(50, 218, 159, 0.14), transparent 26%),
    linear-gradient(145deg, rgba(255, 255, 255, 0.78), rgba(246, 255, 251, 0.52));
  box-shadow: 0 28px 80px rgba(39, 89, 70, 0.1), inset 0 1px 0 rgba(255, 255, 255, 0.9);
  backdrop-filter: blur(22px);
}

.workspace-login .showcase-section::after {
  right: -70px;
  bottom: -110px;
  width: 310px;
  height: 310px;
  border-color: rgba(20, 183, 119, 0.14);
  box-shadow:
    0 0 0 48px rgba(38, 201, 142, 0.045),
    0 0 0 96px rgba(55, 133, 244, 0.025);
}

.workspace-login .showcase-content {
  display: flex;
  flex-direction: column;
  width: 100%;
  max-width: 880px;
  height: 100%;
}

.workspace-login .showcase-eyebrow {
  margin-bottom: 10px;
  color: #447366;
  font-size: 10px;
}

.workspace-login .showcase-eyebrow__icon {
  width: 23px;
  height: 23px;
  border: 1px solid rgba(26, 185, 123, 0.18);
  background: linear-gradient(135deg, #d9faea, #e5f1ff);
  color: #078b61;
  box-shadow: 0 6px 18px rgba(25, 172, 112, 0.12);
}

.workspace-login .showcase-subtitle {
  max-width: 14em;
  margin: 0 0 8px;
  color: #122b23;
  font-size: clamp(32px, 2.5vw, 44px);
  font-weight: 720;
  line-height: 1.08;
  letter-spacing: -0.045em;
  text-shadow: none;
}

.workspace-login .showcase-description {
  margin: 0 0 13px;
  color: #60766d;
  font-size: 13px;
  line-height: 1.55;
}

.workspace-login .feature-tags {
  gap: 7px;
  margin-bottom: 14px;
}

.workspace-login .tag {
  padding: 6px 10px;
  border-color: rgba(133, 181, 163, 0.34);
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.68);
  color: #345c4f;
  font-size: 11px;
  box-shadow: 0 5px 16px rgba(35, 89, 69, 0.05);
}

.workspace-login .feature-stage {
  flex: 1 1 auto;
  width: min(100%, 780px);
  height: clamp(250px, 36vh, 320px);
  min-height: 0;
  margin-top: auto;
  border-color: rgba(137, 179, 165, 0.36);
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.74);
  box-shadow: 0 24px 58px rgba(34, 80, 63, 0.12), inset 0 1px 0 #fff;
}

.workspace-login .feature-stage__rail {
  width: 38px;
  padding: 16px 0;
  border-color: rgba(139, 177, 164, 0.28);
  background: rgba(248, 253, 250, 0.88);
}

.workspace-login .feature-swiper {
  height: 100%;
  min-height: 0;
  margin-left: 38px;
}

.workspace-login .feature-swiper :deep(.swiper-wrapper),
.workspace-login .feature-swiper :deep(.swiper-slide) {
  height: 100%;
  min-height: 0;
}

.workspace-login .feature-scene {
  grid-template-columns: minmax(190px, 0.66fr) minmax(0, 1.34fr);
  height: 100%;
  min-height: 0;
}

.workspace-login .feature-scene__copy {
  padding: 24px 16px 38px 28px;
  background: linear-gradient(90deg, rgba(255, 255, 255, 0.98) 76%, rgba(255, 255, 255, 0));
}

.workspace-login .feature-scene__copy h3 {
  margin: 9px 0 7px;
  font-size: 19px;
}

.workspace-login .feature-scene__visual,
.workspace-login .slide-image {
  height: 100%;
  min-height: 0;
}

.workspace-login .form-section {
  position: relative;
  grid-column: 2;
  grid-row: 2;
  align-items: center;
  min-width: 0;
  min-height: 0;
  height: auto;
  padding: 18px 28px 24px;
  overflow: hidden;
  border: 1px solid rgba(255, 255, 255, 0.82);
  border-radius: 28px;
  background:
    radial-gradient(circle at 88% 4%, rgba(78, 140, 255, 0.18), transparent 30%),
    radial-gradient(circle at 6% 92%, rgba(35, 220, 151, 0.2), transparent 34%),
    linear-gradient(145deg, rgba(255, 255, 255, 0.62), rgba(241, 251, 247, 0.46));
  box-shadow: 0 28px 80px rgba(39, 89, 70, 0.1), inset 0 1px 0 rgba(255, 255, 255, 0.9);
  backdrop-filter: blur(22px);
}

.workspace-login .form-section::before {
  content: '';
  position: absolute;
  top: 7%;
  right: -34%;
  width: 280px;
  height: 280px;
  border: 1px solid rgba(72, 139, 255, 0.12);
  border-radius: 50%;
  box-shadow: 0 0 0 42px rgba(72, 139, 255, 0.025), 0 0 0 84px rgba(30, 207, 142, 0.025);
  pointer-events: none;
}

.workspace-login .form-section::after {
  content: 'SECURE KNOWLEDGE ACCESS';
  position: absolute;
  right: 22px;
  bottom: 14px;
  color: rgba(31, 91, 71, 0.3);
  font-size: 8px;
  font-weight: 750;
  letter-spacing: 0.2em;
}

.workspace-login .form-panel {
  position: relative;
  z-index: 2;
  width: 100%;
  max-width: 430px;
  max-height: 100%;
  margin: 0 auto;
}

.workspace-login .form-card {
  width: 100%;
  max-height: 100%;
  padding: clamp(24px, 2vw, 30px);
  overflow-y: auto;
  border: 1px solid rgba(255, 255, 255, 0.92);
  border-radius: 24px;
  background: linear-gradient(145deg, rgba(255, 255, 255, 0.94), rgba(247, 255, 251, 0.8));
  box-shadow:
    0 30px 70px rgba(32, 76, 60, 0.14),
    0 10px 26px rgba(50, 102, 176, 0.07),
    inset 0 1px 0 #fff;
  backdrop-filter: blur(28px);
  scrollbar-width: none;

  &::-webkit-scrollbar {
    display: none;
  }
}

.workspace-login .form-header {
  margin-bottom: 18px;
}

.workspace-login .form-title {
  margin-bottom: 6px;
  color: #15382d;
  font-size: 26px;
}

.workspace-login .form-welcome,
.workspace-login .form-subtitle {
  color: #6b8078;
  font-size: 11px;
  line-height: 1.5;
}

.workspace-login .form-hint {
  margin-top: 10px;
  padding: 8px 10px;
  border-color: rgba(37, 184, 126, 0.2);
  background: linear-gradient(90deg, rgba(224, 249, 237, 0.92), rgba(231, 243, 255, 0.72));
  color: #247054;
}

.workspace-login .form-content :deep(.t-form-item) {
  margin-bottom: 12px;
}

.workspace-login .form-content :deep(.t-form-item__label) {
  margin-bottom: 5px;
  color: #385b50;
  font-size: 12px;
}

.workspace-login .form-content :deep(.t-input) {
  min-height: 42px;
  border-color: rgba(137, 177, 164, 0.42);
  border-radius: 11px;
  background: rgba(255, 255, 255, 0.66);
  transition: border-color 0.2s ease, box-shadow 0.2s ease, background 0.2s ease;
}

.workspace-login .form-content :deep(.t-input:hover) {
  border-color: #7dbba3;
  background: rgba(255, 255, 255, 0.88);
}

.workspace-login .form-content :deep(.t-input:focus-within) {
  border-color: #16a871;
  background: #fff;
  box-shadow: 0 0 0 3px rgba(22, 168, 113, 0.11), 0 8px 22px rgba(42, 112, 85, 0.08);
}

.workspace-login .submit-button {
  height: 42px;
  margin: 12px 0 11px;
  border: 0;
  border-radius: 11px;
  background: linear-gradient(105deg, #096d55 0%, #0eaa70 55%, #3b8ff4 125%);
  box-shadow: 0 12px 28px rgba(14, 160, 107, 0.24);
}

.workspace-login .submit-button:hover {
  border: 0;
  background: linear-gradient(105deg, #075f4a 0%, #0a9662 55%, #317fd9 125%);
  box-shadow: 0 15px 32px rgba(14, 160, 107, 0.28);
  transform: translateY(-1px);
}

.workspace-login .register-cta__button,
.workspace-login .oidc-button {
  height: 41px;
  border-radius: 11px;
}

.workspace-login .register-cta__button {
  border-color: rgba(90, 155, 132, 0.46);
  background: rgba(255, 255, 255, 0.38);
  color: #176b52;
}

.workspace-login .register-cta__button:hover {
  border-color: #55a98a;
  background: rgba(237, 252, 245, 0.86);
  color: #0e6048;
}

.workspace-login .register-cta__divider span,
.workspace-login .oidc-divider span {
  background: rgba(251, 255, 253, 0.88);
}

.workspace-login .login-features {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 6px;
  margin-top: 14px;
  padding-top: 13px;
  border-top-color: rgba(127, 170, 154, 0.22);
}

.workspace-login .login-features .feature-item {
  flex-direction: row;
  align-items: center;
  gap: 5px;
  min-width: 0;
  color: #677d75;
  font-size: 9px;
  line-height: 1.25;
}

.workspace-login .login-features .feature-icon {
  flex: 0 0 auto;
  width: 16px;
  height: 16px;
  margin: 0;
  background: linear-gradient(135deg, #dcf8e9, #e5efff);
  color: #0b9864;
}

@media (max-width: 1180px) {
  .workspace-login.workspace-login {
    grid-template-columns: minmax(0, 1.16fr) minmax(380px, 0.84fr);
  }

  .workspace-login .showcase-section {
    padding-right: 22px;
    padding-left: 24px;
  }

  .workspace-login .form-section {
    padding-right: 20px;
    padding-left: 20px;
  }
}

@media (max-width: 900px) {
  .workspace-login.workspace-login {
    grid-template-columns: 1fr;
    grid-template-rows: 54px auto auto;
    height: auto;
    min-height: 100vh;
    padding: 10px;
    overflow-y: auto;
  }

  .workspace-login .brand-wordmark,
  .workspace-login .header-links {
    grid-column: 1;
    grid-row: 1;
  }

  .workspace-login .brand-wordmark {
    margin-left: 12px;
  }

  .workspace-login .header-links {
    margin-right: 10px;
  }

  .workspace-login .showcase-section {
    grid-column: 1;
    grid-row: 2;
    min-height: auto;
    padding: 24px 20px;
  }

  .workspace-login .showcase-content {
    height: auto;
  }

  .workspace-login .showcase-subtitle {
    font-size: 34px;
  }

  .workspace-login .feature-stage {
    flex: none;
    height: 300px;
  }

  .workspace-login .form-section {
    grid-column: 1;
    grid-row: 3;
    min-height: auto;
    padding: 30px 20px 44px;
  }

  .workspace-login .form-panel,
  .workspace-login .form-card {
    max-height: none;
  }

  .workspace-login .form-card {
    overflow: visible;
  }
}

@media (max-width: 560px) {
  .workspace-login .brand-wordmark__zh {
    font-size: 18px;
  }

  .workspace-login .brand-wordmark__en {
    font-size: 13px;
  }

  .workspace-login .language-switch button .link-text {
    display: inline;
  }

  .workspace-login .showcase-section {
    padding: 20px 14px 16px;
    border-radius: 22px;
  }

  .workspace-login .showcase-subtitle {
    font-size: 28px;
  }

  .workspace-login .feature-stage {
    height: 332px;
    border-radius: 16px;
  }

  .workspace-login .feature-stage__rail {
    display: none;
  }

  .workspace-login .feature-swiper {
    margin-left: 0;
  }

  .workspace-login .feature-scene {
    grid-template-columns: 1fr;
    grid-template-rows: 124px 208px;
  }

  .workspace-login .feature-scene__copy {
    padding: 16px 18px 24px;
    background: rgba(255, 255, 255, 0.98);
  }

  .workspace-login .feature-scene__copy h3 {
    margin: 5px 0 4px;
    font-size: 17px;
  }

  .workspace-login .form-section {
    padding: 22px 10px 34px;
    border-radius: 22px;
  }

  .workspace-login .form-card {
    padding: 24px 20px;
  }

  .workspace-login .login-features {
    grid-template-columns: 1fr;
  }

  .workspace-login .login-features .feature-item {
    font-size: 10px;
  }
}
</style>

<style lang="less">
html[theme-mode="dark"] {
  .workspace-login.workspace-login {
    background:
      linear-gradient(rgba(194, 232, 211, 0.035) 1px, transparent 1px),
      linear-gradient(90deg, rgba(194, 232, 211, 0.035) 1px, transparent 1px),
      #111914;
    background-size: 32px 32px;
  }

  .workspace-login .showcase-section {
    background: transparent;
  }

  .workspace-login .brand-wordmark,
  .workspace-login .showcase-subtitle,
  .workspace-login .form-title {
    color: #edf6f1;
  }

  .workspace-login .showcase-description,
  .workspace-login .form-welcome,
  .workspace-login .form-subtitle {
    color: #98aaa0;
  }

  .workspace-login .tag,
  .workspace-login .feature-stage,
  .workspace-login .form-card {
    border-color: #304139;
    background: rgba(24, 35, 29, 0.96);
  }

  .workspace-login .feature-stage__rail,
  .workspace-login .feature-scene__copy {
    border-color: #304139;
    background: #19251f;
  }

  .workspace-login .feature-scene__copy h3 {
    color: #edf6f1;
  }

  .workspace-login .form-section {
    border-color: #2b3d34;
    background: rgba(20, 30, 25, 0.88);
  }

  .workspace-login .form-content .t-input {
    border-color: #35493e !important;
    background: #111a15 !important;
  }
}
</style>
