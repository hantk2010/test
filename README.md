<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:id="@+id/keyboard_height"
    android:layout_width="fill_parent"
    android:layout_height="wrap_content"
    android:layout_alignParentBottom="true"
    android:background="@color/diy_art_box_color">

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content">

        <RelativeLayout
            android:id="@+id/contents"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_alignParentTop="true">

            <ImageView
                android:id="@+id/gif_imageview"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:adjustViewBounds="true"
                android:scaleType="fitXY" />

            <FrameLayout
                android:id="@+id/contentmove_framelayout"
                android:layout_width="match_parent"
                android:layout_height="@dimen/set_height"
                android:visibility="visible">

            </FrameLayout>

            <FrameLayout
                android:id="@+id/content_framelayout"
                android:layout_width="match_parent"
                android:layout_height="@dimen/set_height"
                android:clipChildren="false"
                android:visibility="visible">

            </FrameLayout>

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="40dp"
                android:background="@color/white"
                android:visibility="gone">

                <com.balysv.materialripple.MaterialRippleLayout
                    android:layout_width="50dp"
                    android:layout_height="match_parent"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:layout_marginLeft="10dp"
                            android:src="@drawable/ic_backword" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>


                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_centerInParent="true"
                    android:text="@string/art"
                    android:textSize="16dp" />

                <com.balysv.materialripple.MaterialRippleLayout
                    android:layout_width="50dp"
                    android:layout_height="match_parent"
                    android:layout_alignParentRight="true"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:layout_marginRight="10dp"
                            android:src="@drawable/ic_keyboardword" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>

            </RelativeLayout>

            <RelativeLayout
                android:id="@+id/lang_top"
                android:layout_width="match_parent"
                android:layout_height="40dp"
                android:background="@color/diy_main_bg_color"
                android:visibility="gone">

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/lay_lang_backword"
                    android:layout_width="50dp"
                    android:layout_height="match_parent"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:id="@+id/lang_backword"
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:layout_marginLeft="10dp"
                            android:src="@drawable/ic_backword" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>


                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_centerInParent="true"
                    android:text=" Language "
                    android:textColor="@color/white"
                    android:textSize="16dp" />

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/lay_lang_keyboardword"
                    android:layout_width="50dp"
                    android:layout_height="match_parent"
                    android:layout_alignParentRight="true"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:id="@+id/lang_keyboardword"
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:layout_marginRight="10dp"
                            android:src="@drawable/ic_keyboardword" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>
            </RelativeLayout>

            <RelativeLayout
                android:id="@+id/Menu_top"
                android:layout_width="match_parent"
                android:layout_height="40dp"
                android:background="@color/diy_art_box_color"
                android:visibility="gone">

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/lay_Menu_backword"
                    android:layout_width="50dp"
                    android:layout_height="match_parent"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:id="@+id/Menu_backword"
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:layout_marginLeft="10dp"
                            android:src="@drawable/ic_backword" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_centerInParent="true"
                    android:text=" Menu "
                    android:textColor="@color/diy_font_color"
                    android:textSize="16dp" />

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/lay_Menu_keyboardword"
                    android:layout_width="50dp"
                    android:layout_height="match_parent"
                    android:layout_alignParentRight="true"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:id="@+id/Menu_keyboardword"
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:layout_marginRight="10dp"
                            android:src="@drawable/ic_keyboardword" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>
            </RelativeLayout>


            <LinearLayout
                android:id="@+id/rl_top"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:gravity="center_vertical"
                android:orientation="horizontal">

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/menu_lin"
                    android:layout_width="40dp"
                    android:layout_height="40dp"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:gravity="center">

                        <ImageView
                            android:id="@+id/btnTheme"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_centerHorizontal="true"
                            android:layout_gravity="center" />

                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:layout_gravity="center"
                    android:gravity="center">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:layout_gravity="center"
                        android:gravity="center">


                        <LinearLayout
                            android:id="@+id/mainMenuLay"
                            android:layout_width="match_parent"
                            android:layout_height="match_parent"
                            android:layout_gravity="center"
                            android:gravity="center"
                            android:orientation="horizontal"
                            android:visibility="visible">

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:id="@+id/lay_emoji"
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center">

                                    <ImageView
                                        android:id="@+id/btn_emoji"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:id="@+id/lay_theme"
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:id="@+id/lin_theme"
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center">

                                    <ImageView
                                        android:id="@+id/ic_themeLay"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                android:visibility="gone"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center">

                                    <ImageView
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center"
                                        android:background="@drawable/ic_glf_default" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                android:visibility="gone"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center">

                                    <ImageView
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center"
                                        android:background="@drawable/ic_art28" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:layout_width="match_parent"

                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                android:visibility="gone"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center">

                                    <ImageView
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center"
                                        android:background="@drawable/ic_setting_default" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>


                            <com.balysv.materialripple.MaterialRippleLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                android:visibility="gone"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center"
                                    android:visibility="gone">

                                    <ImageView
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center"
                                        android:background="@drawable/ic_volume_default" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:id="@+id/lay_voice"
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center">

                                    <ImageView
                                        android:id="@+id/ic_voice_keybord"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                android:visibility="invisible"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center">

                                    <ImageView
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                android:visibility="invisible"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center">

                                    <ImageView
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                android:visibility="invisible"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center">

                                    <ImageView
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:id="@+id/top_game_lay1"
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                android:visibility="gone"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center">

                                    <ImageView
                                        android:id="@+id/top_menu_game"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center"
                                        android:src="@drawable/top_menu_game" />
                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:id="@+id/lay_fancy"
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="1"
                                android:visibility="gone"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:id="@+id/lin_fancy"
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:layout_gravity="center"
                                    android:gravity="center"
                                    android:visibility="gone">

                                    <ImageView
                                        android:id="@+id/btn_fancyFont"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_gravity="center"
                                        android:background="@drawable/ic_fancy_default" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>

                            <com.balysv.materialripple.MaterialRippleLayout
                                android:id="@+id/lay_close"
                                android:layout_width="match_parent"
                                android:layout_height="40dp"
                                android:layout_weight="1"
                                app:mrl_rippleColor="@color/mr_rippleColor"
                                app:mrl_rippleDelayClick="false"
                                app:mrl_rippleDuration="@integer/rippleDuration"
                                app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                app:mrl_rippleHover="true"
                                app:mrl_rippleOverlay="true"
                                app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:gravity="center">

                                    <ImageView
                                        android:id="@+id/closeImeButton"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_centerInParent="true"
                                        android:layout_gravity="center" />

                                </RelativeLayout>
                            </com.balysv.materialripple.MaterialRippleLayout>
                        </LinearLayout>


                        <com.fx.neon.led.keyboard.widgets.CandidateView
                            android:id="@+id/mCandidateView"
                            android:layout_width="match_parent"
                            android:layout_height="@dimen/candidate_strip_height"
                            android:layout_centerVertical="true"
                            android:layout_marginRight="5dp" />
                    </RelativeLayout>

                </LinearLayout>


            </LinearLayout>

            <RelativeLayout
                android:id="@+id/contents1"
                android:layout_width="fill_parent"
                android:layout_height="wrap_content"
                android:layout_below="@+id/rl_top">


                <com.fx.neon.led.keyboard.widgets.MyKeyboardView
                    android:id="@+id/keyboard"
                    style="@style/Widget.KeyboardView10"
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginTop="3.0dip"
                    android:verticalCorrection="0.0dip" />

                <RelativeLayout
                    android:id="@+id/customMenulay"
                    android:layout_width="fill_parent"
                    android:layout_height="@dimen/set_height"
                    android:gravity="center"
                    android:visibility="gone" />
                <!--    for show all list on menu Click-->

                <RelativeLayout
                    android:id="@+id/themeMenulay"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:background="@color/diy_main_bg_color"
                    android:gravity="center"
                    android:visibility="gone">


                    <ScrollView
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:layout_centerInParent="true"
                        android:layout_marginTop="2dp"
                        android:layout_marginBottom="5dp"
                        android:scrollbars="none">

                        <LinearLayout
                            android:layout_width="match_parent"
                            android:layout_height="wrap_content"
                            android:layout_margin="3dp"
                            android:orientation="vertical"
                            android:weightSum="5">

                            <LinearLayout
                                android:layout_width="match_parent"
                                android:layout_height="wrap_content"
                                android:layout_gravity="center"
                                android:layout_weight="1"
                                android:gravity="center"
                                android:orientation="horizontal"
                                android:weightSum="4">
                                <!--theme11-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btninsideTheme"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btninsideTheme"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--Lang-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnLanguage"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnLanguage"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--DIY-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnDIY"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnDIY"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--Setting-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnSetting"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnSetting"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>


                            </LinearLayout>

                            <LinearLayout
                                android:id="@+id/lin_effect"
                                android:layout_width="match_parent"
                                android:layout_height="wrap_content"
                                android:layout_weight="1"
                                android:orientation="horizontal"
                                android:weightSum="4">
                                <!--Effect On Off-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnEffect"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnEffect"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                    <!--android:src="@drawable/effect_off"-->

                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--EffectList-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnEffectList"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnEffectList"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                    <!--android:src="@drawable/key_effect"-->
                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--                                Share-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnShare1"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    android:visibility="visible"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnShare1"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />

                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--rate-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_rate1"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    android:visibility="visible"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnRate1"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />

                                </com.balysv.materialripple.MaterialRippleLayout>
                                Touch Effect On Off

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnTouchEffect"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btntouchEffect"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                    <!--android:src="@drawable/effect_off"-->

                                </com.balysv.materialripple.MaterialRippleLayout>
                                Touch EffectList

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnTouchEffectList"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnTouchEffectList"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                    <!--android:src="@drawable/key_effect"-->
                                </com.balysv.materialripple.MaterialRippleLayout>


                            </LinearLayout>

                            <LinearLayout
                                android:layout_width="match_parent"
                                android:layout_height="wrap_content"
                                android:layout_weight="1"
                                android:orientation="horizontal"
                                android:weightSum="4">
                                <!--popup-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnKeyPopup"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnKeyPopup"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true" />
                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--btnNumeric-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnNumeric"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnNumeric"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--NumericEmoji-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnemoji_Numeric"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnemoji_Numeric"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />

                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--Autocurrect-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnautocurract"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnautocurract"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>


                            </LinearLayout>

                            <LinearLayout
                                android:layout_width="match_parent"
                                android:layout_height="wrap_content"
                                android:layout_weight="1"
                                android:orientation="horizontal"
                                android:weightSum="4">

                                <!--Font-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnFonts"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnFonts"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>

                                <!--soundon/off-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnSoundOnOff"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnSoundOnOff"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true" />

                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--sound-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnSound"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnSound"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--vibrate-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnVibrateOnOff"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnVibrateOnOff"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>

                            </LinearLayout>


                            <LinearLayout
                                android:layout_width="match_parent"
                                android:layout_height="wrap_content"
                                android:layout_weight="1"
                                android:orientation="horizontal"
                                android:visibility="visible"
                                android:weightSum="4">

                                <!--Clipboard-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnClipboard"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnClipboard"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>

                                <!--Share-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_btnShare"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnShare"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />

                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_rate"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnRate"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />

                                </com.balysv.materialripple.MaterialRippleLayout>

                                <!--//keyboard size-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_ad01110"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    android:visibility="visible"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:visibility="gone"
                                        android:adjustViewBounds="true"
                                        android:gravity="center"
                                        android:src="@drawable/keyboard_height_resize" />
                                </com.balysv.materialripple.MaterialRippleLayout>

                            </LinearLayout>

                            <LinearLayout
                                android:layout_width="match_parent"
                                android:layout_height="wrap_content"
                                android:layout_weight="1"
                                android:orientation="horizontal"
                                android:visibility="gone"
                                android:weightSum="4">
                                <!--rate-->

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_rate11"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnRate11"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />

                                </com.balysv.materialripple.MaterialRippleLayout>

                                <!--Ad-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_ad"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnad"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />

                                </com.balysv.materialripple.MaterialRippleLayout>
                                <!--Custom Ad1-->
                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/lay_ad1"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <ImageView
                                        android:id="@+id/btnad1"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_margin="3dp"
                                        android:layout_weight="1"
                                        android:adjustViewBounds="true"
                                        android:gravity="center" />
                                </com.balysv.materialripple.MaterialRippleLayout>

                            </LinearLayout>
                        </LinearLayout>
                    </ScrollView>

                </RelativeLayout>


                <RelativeLayout
                    android:id="@+id/customText_option_pad"
                    android:layout_width="fill_parent"
                    android:layout_height="@dimen/set_height"
                    android:gravity="center"
                    android:visibility="gone" />

                <RelativeLayout
                    android:layout_width="fill_parent"
                    android:layout_height="@dimen/set_height"
                    android:gravity="center"
                    android:visibility="gone">

                    <GridView
                        android:id="@+id/gridView1"
                        android:layout_width="fill_parent"
                        android:layout_height="fill_parent"
                        android:numColumns="4" />
                </RelativeLayout>

                <LinearLayout
                    android:id="@+id/keyboardly"
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:background="@color/diy_art_box_color"
                    android:gravity="center"
                    android:orientation="horizontal"
                    android:visibility="gone"
                    android:weightSum="2.0">

                    <LinearLayout
                        android:layout_width="0.0dip"
                        android:layout_height="fill_parent"
                        android:layout_weight="1.0"
                        android:background="@color/diy_art_box_color"
                        android:gravity="center"
                        android:orientation="vertical">

                        <ImageButton
                            android:id="@+id/setKeyboardLay1Btn"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_marginLeft="3.0dip"
                            android:layout_marginRight="3.0dip"
                            android:background="@drawable/twentysixpressxml" />

                        <ImageButton
                            android:id="@+id/setKeyboardLay2Btn"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_marginLeft="3.0dip"
                            android:layout_marginRight="3.0dip"
                            android:background="@drawable/ninethemepressxml"
                            android:visibility="visible" />
                    </LinearLayout>

                    <LinearLayout
                        android:layout_width="0.0dip"
                        android:layout_height="fill_parent"
                        android:layout_weight="1.0"
                        android:background="@color/diy_art_box_color"
                        android:orientation="vertical">

                        <ListView
                            android:id="@+id/keyboardlang"
                            android:layout_width="fill_parent"
                            android:layout_height="fill_parent" />
                    </LinearLayout>
                </LinearLayout>
            </RelativeLayout>

            <!--    for Voice View Data-->

            <LinearLayout
                android:id="@+id/root_layout"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:background="@color/diy_art_box_color"
                android:orientation="vertical"
                android:visibility="gone"
                android:weightSum="2">

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:layout_marginTop="45dp"
                    android:layout_weight="0.6"
                    android:orientation="horizontal"
                    android:weightSum="3">

                    <LinearLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:layout_gravity="center"
                        android:layout_marginLeft="15dp"
                        android:layout_weight="1">

                        <com.balysv.materialripple.MaterialRippleLayout
                            android:id="@+id/voiceselecton_rel_lay"
                            android:layout_width="match_parent"
                            android:layout_height="match_parent"
                            android:layout_gravity="center"
                            android:layout_weight="1"
                            android:visibility="visible"
                            app:mrl_rippleColor="@color/mr_rippleColor"
                            app:mrl_rippleDelayClick="false"
                            app:mrl_rippleDuration="@integer/rippleDuration"
                            app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                            app:mrl_rippleHover="true"
                            app:mrl_rippleOverlay="true"
                            app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">


                            <RelativeLayout
                                android:id="@+id/voiceselecton_rel"
                                android:layout_width="match_parent"
                                android:layout_height="match_parent">

                                <ImageView
                                    android:id="@+id/langselection1"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:layout_centerInParent="true"
                                    android:background="@drawable/launguagevoice" />

                                <com.fx.neon.led.keyboard.widgets.CustomTextViewSubTitle
                                    android:id="@+id/lang12"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:layout_below="@id/langselection1"
                                    android:layout_centerHorizontal="true"
                                    android:singleLine="true"
                                    android:text="English"
                                    android:textColor="@color/diy_header_color"
                                    android:textSize="16dp" />

                            </RelativeLayout>
                        </com.balysv.materialripple.MaterialRippleLayout>
                    </LinearLayout>

                    <LinearLayout
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:layout_gravity="center"
                        android:layout_weight="1">

                        <LinearLayout
                            android:layout_width="match_parent"
                            android:layout_height="wrap_content"
                            android:orientation="vertical">

                            <FrameLayout
                                android:id="@+id/flvoid"
                                android:layout_width="90.0dip"
                                android:layout_height="90.0dip"
                                android:layout_centerInParent="true"
                                android:layout_gravity="center"
                                android:background="@color/diy_art_box_color">

                                <ImageView
                                    android:layout_width="fill_parent"
                                    android:layout_height="fill_parent"
                                    android:layout_gravity="center"
                                    android:src="@drawable/togglebutton_on" />

                                <ImageView
                                    android:id="@+id/imgvoid"
                                    android:layout_width="fill_parent"
                                    android:layout_height="fill_parent"
                                    android:layout_gravity="center"
                                    android:src="@drawable/voice_toggle" />

                                <ImageButton
                                    android:id="@+id/btnspeech"
                                    android:layout_width="fill_parent"
                                    android:layout_height="fill_parent"
                                    android:layout_gravity="center"
                                    android:background="@drawable/togglebuttonbg"
                                    android:visibility="visible" />

                                <ProgressBar
                                    android:id="@+id/progressBarTalk"
                                    android:layout_width="50.0dip"
                                    android:layout_height="50.0dip"
                                    android:layout_gravity="center"
                                    android:layout_marginBottom="2.0dip"
                                    android:keepScreenOn="true"
                                    android:visibility="invisible" />

                            </FrameLayout>

                            <com.fx.neon.led.keyboard.widgets.CustomTextViewSubTitle
                                android:id="@+id/speaktext"
                                android:layout_width="match_parent"
                                android:layout_height="wrap_content"
                                android:layout_below="@+id/flvoid"
                                android:layout_marginTop="6dp"
                                android:gravity="center_horizontal"
                                android:text="Tap To Start"
                                android:textColor="@color/white"
                                android:textSize="16dp" />

                        </LinearLayout>

                    </LinearLayout>

                    <LinearLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:layout_gravity="center"
                        android:layout_weight="1">

                        <com.balysv.materialripple.MaterialRippleLayout
                            android:id="@+id/dialog_erase_lay"
                            android:layout_width="match_parent"
                            android:layout_height="match_parent"
                            android:layout_gravity="center"
                            android:layout_marginRight="15dp"
                            app:mrl_rippleColor="@color/mr_rippleColor"
                            app:mrl_rippleDelayClick="false"
                            app:mrl_rippleDuration="@integer/rippleDuration"
                            app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                            app:mrl_rippleHover="true"
                            app:mrl_rippleOverlay="true"
                            app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                            <RelativeLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent">

                                <ImageView
                                    android:id="@+id/dialog_erase"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:layout_centerInParent="true"
                                    android:background="@drawable/ic_del_voicetext" />
                            </RelativeLayout>
                        </com.balysv.materialripple.MaterialRippleLayout>
                    </LinearLayout>
                </LinearLayout>

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:layout_marginBottom="10dp"
                    android:layout_weight="1.4">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:layout_gravity="center"
                        android:layout_marginTop="2dp">

                        <LinearLayout
                            android:layout_width="match_parent"
                            android:layout_height="wrap_content"
                            android:gravity="bottom"
                            android:orientation="vertical"
                            android:visibility="visible"
                            android:weightSum="2">

                            <LinearLayout
                                android:layout_width="match_parent"
                                android:layout_height="wrap_content"
                                android:layout_marginLeft="10dp"
                                android:layout_marginTop="5dp"
                                android:layout_marginRight="10dp"
                                android:layout_weight="1"
                                android:gravity="center"
                                android:orientation="horizontal"
                                android:weightSum="7">

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/text_string_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="match_parent"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/text_string"
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:gravity="center">

                                        <TextView
                                            android:layout_width="match_parent"
                                            android:layout_height="match_parent"
                                            android:layout_gravity="center"
                                            android:gravity="center"
                                            android:text="@"
                                            android:textColor="@color/white" />
                                    </LinearLayout>

                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/text_dot_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="match_parent"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/text_dot"
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:gravity="center">

                                        <TextView
                                            android:layout_width="match_parent"
                                            android:layout_height="match_parent"
                                            android:layout_gravity="center"
                                            android:gravity="center"
                                            android:text="."
                                            android:textColor="@color/white" />
                                    </LinearLayout>

                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/text_qotes_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="match_parent"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/text_qotes"
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:gravity="center">

                                        <TextView
                                            android:layout_width="match_parent"
                                            android:layout_height="match_parent"
                                            android:layout_gravity="center"
                                            android:gravity="center"
                                            android:text="@string/double_qutoes"
                                            android:textColor="@color/white" />
                                    </LinearLayout>

                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/text_comma_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="match_parent"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/text_comma"
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:gravity="center">

                                        <TextView
                                            android:layout_width="match_parent"
                                            android:layout_height="match_parent"
                                            android:layout_gravity="center"
                                            android:gravity="center"
                                            android:text=","
                                            android:textColor="@color/white" />
                                    </LinearLayout>

                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/text_quetion_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="match_parent"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/text_quetion"
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:gravity="center">

                                        <TextView
                                            android:layout_width="match_parent"
                                            android:layout_height="match_parent"
                                            android:layout_gravity="center"
                                            android:gravity="center"
                                            android:text="?"
                                            android:textColor="@color/white" />
                                    </LinearLayout>

                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/text_desh_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="match_parent"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/text_desh"
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:gravity="center">

                                        <TextView
                                            android:layout_width="match_parent"
                                            android:layout_height="match_parent"
                                            android:layout_gravity="center"
                                            android:gravity="center"
                                            android:text="-"
                                            android:textColor="@color/white" />
                                    </LinearLayout>

                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/text_Exclamation_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="match_parent"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/text_Exclamation"
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:gravity="center">

                                        <TextView
                                            android:layout_width="match_parent"
                                            android:layout_height="match_parent"
                                            android:layout_gravity="center"
                                            android:gravity="center"
                                            android:text="!"
                                            android:textColor="@color/white" />
                                    </LinearLayout>

                                </com.balysv.materialripple.MaterialRippleLayout>
                            </LinearLayout>

                            <LinearLayout
                                android:layout_width="match_parent"
                                android:layout_height="wrap_content"
                                android:layout_marginLeft="10dp"
                                android:layout_marginTop="10dp"
                                android:layout_marginRight="10dp"
                                android:layout_weight="1"
                                android:gravity="center"
                                android:orientation="horizontal"
                                android:weightSum="7">

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/emoji_glase_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="match_parent"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/emoji_glase"
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:gravity="center">

                                        <ImageView
                                            android:layout_width="match_parent"
                                            android:layout_height="match_parent"
                                            android:layout_gravity="center"
                                            android:adjustViewBounds="true"
                                            android:gravity="center"
                                            android:src="@drawable/emoji_1f60e" />
                                    </LinearLayout>
                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/emoji_smile_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/emoji_smile"
                                        android:layout_width="match_parent"
                                        android:layout_height="wrap_content"
                                        android:gravity="center">

                                        <ImageView
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_gravity="center"
                                            android:adjustViewBounds="true"
                                            android:gravity="center"
                                            android:src="@drawable/emoji_1f60d" />
                                    </LinearLayout>
                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/emoji_eye_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/emoji_eye"
                                        android:layout_width="match_parent"
                                        android:layout_height="wrap_content"
                                        android:gravity="center">

                                        <ImageView
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_gravity="center"
                                            android:adjustViewBounds="true"
                                            android:gravity="center"
                                            android:src="@drawable/emoji_1f61c" />
                                    </LinearLayout>
                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/emoji_tung_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/emoji_tung"
                                        android:layout_width="match_parent"
                                        android:layout_height="wrap_content"
                                        android:gravity="center">

                                        <ImageView
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_gravity="center"
                                            android:adjustViewBounds="true"
                                            android:gravity="center"
                                            android:src="@drawable/emoji_1f614" />
                                    </LinearLayout>
                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/emoji_laugh_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/emoji_laugh"
                                        android:layout_width="match_parent"
                                        android:layout_height="wrap_content"
                                        android:gravity="center">

                                        <ImageView
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_gravity="center"
                                            android:adjustViewBounds="true"
                                            android:gravity="center"
                                            android:src="@drawable/emoji_1f61d" />
                                    </LinearLayout>
                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/emoji_shock_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/emoji_shock"
                                        android:layout_width="match_parent"
                                        android:layout_height="wrap_content"
                                        android:gravity="center">

                                        <ImageView
                                            android:id="@+id/emoji_1f62f"
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_gravity="center"
                                            android:adjustViewBounds="true"
                                            android:gravity="center" />
                                    </LinearLayout>
                                </com.balysv.materialripple.MaterialRippleLayout>

                                <com.balysv.materialripple.MaterialRippleLayout
                                    android:id="@+id/emoji_kiss_lay"
                                    android:layout_width="@dimen/actionbar_height"
                                    android:layout_height="wrap_content"
                                    android:layout_weight="1"
                                    app:mrl_rippleColor="@color/mr_rippleColor"
                                    app:mrl_rippleDelayClick="false"
                                    app:mrl_rippleDuration="@integer/rippleDuration"
                                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                                    app:mrl_rippleHover="true"
                                    app:mrl_rippleOverlay="true"
                                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                                    <LinearLayout
                                        android:id="@+id/emoji_kiss"
                                        android:layout_width="match_parent"
                                        android:layout_height="wrap_content"
                                        android:gravity="center">

                                        <ImageView
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_gravity="center"
                                            android:adjustViewBounds="true"
                                            android:gravity="center"
                                            android:src="@drawable/emoji_1f620" />
                                    </LinearLayout>
                                </com.balysv.materialripple.MaterialRippleLayout>
                            </LinearLayout>
                        </LinearLayout>
                    </RelativeLayout>
                </LinearLayout>
            </LinearLayout>

            <RelativeLayout
                android:id="@+id/rel1"
                android:layout_width="match_parent"
                android:layout_height="40dp"
                android:background="@color/diy_main_bg_color"
                android:visibility="gone">

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/lay_voice_backword"
                    android:layout_width="50dp"
                    android:layout_height="match_parent"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <androidx.appcompat.widget.AppCompatImageButton
                            android:id="@+id/voice_backword"
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:layout_marginLeft="10dp"
                            android:background="@color/diy_main_bg_color"
                            app:srcCompat="@drawable/ic_back" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_centerInParent="true"
                    android:text="VOICE "
                    android:textColor="@color/white"
                    android:textSize="16dp" />

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/lay_btn_closedialog"
                    android:layout_width="50dp"
                    android:layout_height="match_parent"
                    android:layout_alignParentRight="true"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:id="@+id/btn_closedialog"
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:layout_marginRight="10dp"
                            android:src="@drawable/ic_keyboardword" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>
            </RelativeLayout>
        </RelativeLayout>


        <RelativeLayout
            android:id="@+id/main_emoji"
            android:layout_width="match_parent"
            android:layout_height="@dimen/set_height"
            android:background="@color/diy_main_bg_color"
            android:visibility="gone">

            <RelativeLayout
                android:id="@+id/emojiLayout"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_above="@+id/below_emoji"
                android:visibility="gone">

            </RelativeLayout>

            <RelativeLayout
                android:id="@+id/artMojilayout"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_above="@+id/below_emoji"
                android:visibility="gone">

                <RelativeLayout
                    android:id="@+id/artmoji_top"
                    android:layout_width="match_parent"
                    android:layout_height="34dp"
                    android:background="@color/diy_main_bg_color"
                    android:orientation="horizontal"
                    android:visibility="visible"
                    android:weightSum="2.0">


                    <com.fx.neon.led.keyboard.widgets.MagicIndicator
                        android:id="@+id/textemojiTabLayout"
                        android:layout_width="match_parent"
                        android:layout_height="34dp"
                        android:layout_toLeftOf="@+id/art_download"
                        android:background="@color/diy_main_bg_color" />

                </RelativeLayout>

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_below="@+id/artmoji_top"
                    android:background="@color/diy_art_box_color">
                    <!--                    -->
                    <androidx.viewpager.widget.ViewPager
                        android:id="@+id/art_viewpager"
                        android:layout_width="fill_parent"
                        android:layout_height="match_parent"
                        android:layout_below="@+id/l1"
                        android:layout_marginLeft="3dp"
                        android:layout_marginTop="2dp"
                        android:layout_marginRight="3dp"
                        android:layout_marginBottom="5dp"
                        android:layout_weight="1.0"
                        android:background="@color/diy_main_bg_color" />

                    <ProgressBar
                        android:id="@+id/art_progress"
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_centerInParent="true"
                        android:theme="@style/AppTheme.WhiteAccent"
                        android:visibility="gone" />
                </RelativeLayout>

            </RelativeLayout>

            <RelativeLayout
                android:id="@+id/textmoji_Layout"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_above="@+id/below_emoji"
                android:visibility="gone">

            </RelativeLayout>

            <RelativeLayout
                android:id="@+id/gif_layout"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:background="@color/diy_art_box_color"
                android:visibility="visible">

                <RelativeLayout
                    android:id="@+id/gif_top"
                    android:layout_width="match_parent"
                    android:layout_height="34dp"
                    android:background="@color/diy_main_bg_color"
                    android:orientation="horizontal"
                    android:visibility="gone"
                    android:weightSum="2.0">

                    <androidx.recyclerview.widget.RecyclerView
                        android:id="@+id/gif_categories_view"
                        android:layout_width="match_parent"
                        android:layout_height="34dp"
                        android:layout_marginLeft="8dp"
                        android:layout_marginRight="8dp"
                        android:background="@color/diy_main_bg_color"
                        android:clipToPadding="false"
                        android:paddingRight="10.0dip"
                        android:visibility="visible" />


                </RelativeLayout>

                <RelativeLayout
                    android:id="@+id/gifLay"
                    android:layout_width="fill_parent"
                    android:layout_height="wrap_content"
                    android:layout_below="@+id/gif_top"
                    android:background="@color/diy_main_bg_color"
                    android:visibility="gone">
                    <!-- for tag position2-->
                    <androidx.recyclerview.widget.RecyclerView
                        android:id="@+id/gifcategory_tag"
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:background="@color/colorPrimary"
                        android:paddingBottom="@dimen/_30sdp"
                        android:visibility="gone" />
                    <!--for All array category data-->
                    <androidx.recyclerview.widget.RecyclerView
                        android:id="@+id/all_gifcategory"
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:visibility="visible" />

                    <ProgressBar
                        android:id="@+id/main_progress"
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_centerInParent="true"
                        android:visibility="visible" />

                    <RelativeLayout
                        android:id="@+id/category_tag_activity"
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:background="@color/diy_main_bg_color"
                        android:visibility="gone">

                        <ProgressBar
                            android:id="@+id/category_progress"
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_centerInParent="true"
                            android:visibility="gone" />
                        <!--for tag categry click show data-->
                        <androidx.recyclerview.widget.RecyclerView
                            android:id="@+id/category_tag_gif"
                            android:layout_width="match_parent"
                            android:layout_height="match_parent"
                            android:layout_marginBottom="40dp"
                            android:background="@color/diy_main_bg_color"
                            android:visibility="visible" />

                        <!--                     for tag categry click show data- and back view-->

                        <LinearLayout
                            android:layout_width="match_parent"
                            android:layout_height="45dp"
                            android:layout_alignParentBottom="true"
                            android:layout_marginBottom="40dp"
                            android:background="@color/diy_main_bg_color"
                            android:gravity="center_vertical"
                            android:orientation="horizontal"
                            android:visibility="visible"
                            android:weightSum="1">

                            <androidx.appcompat.widget.AppCompatImageButton
                                android:id="@+id/as_ib_back"
                                android:layout_width="21dp"
                                android:layout_height="21dp"
                                android:layout_centerInParent="true"
                                android:layout_margin="@dimen/dimen_5dp"
                                android:layout_marginLeft="10dp"
                                android:background="@color/diy_main_bg_color"
                                android:contentDescription="search"
                                android:minWidth="56dp"
                                app:srcCompat="@drawable/ic_back" />

                            <TextView
                                android:id="@+id/as_tv_query"
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_marginLeft="10dp"
                                android:layout_weight="1"
                                android:gravity="center_vertical"
                                android:hint="hint"
                                android:maxLines="1"
                                android:textColor="@color/white"
                                android:textColorHint="@color/white"
                                android:textSize="18sp" />
                        </LinearLayout>
                    </RelativeLayout>
                </RelativeLayout>
            </RelativeLayout>

            <!--    for small View for display emoji or gif data-->

            <RelativeLayout
                android:id="@+id/below_emoji"
                android:layout_width="match_parent"
                android:layout_height="40dp"
                android:layout_alignParentBottom="true"
                android:background="@color/diy_main_bg_color">

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/main_emoji_back"
                    android:layout_width="40dp"
                    android:layout_height="match_parent"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <androidx.appcompat.widget.AppCompatImageView
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            app:srcCompat="@drawable/ic_back" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/rel_emoji"
                    android:layout_width="40dp"
                    android:layout_height="match_parent"
                    android:layout_toRightOf="@+id/main_emoji_back"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:id="@+id/emoji"
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:src="@drawable/emojiicon_press" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/rel_sticker"
                    android:layout_width="40dp"
                    android:layout_height="match_parent"
                    android:layout_toRightOf="@+id/rel_emoji"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:id="@+id/sticker"
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:src="@drawable/sticker_unpress" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/rel_textmoji"
                    android:layout_width="40dp"
                    android:layout_height="match_parent"
                    android:layout_toRightOf="@+id/rel_sticker"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:id="@+id/textmoji_view"
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:src="@drawable/kamoji_normal" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>

                <com.balysv.materialripple.MaterialRippleLayout
                    android:id="@+id/rel_artmoji"
                    android:layout_width="40dp"
                    android:layout_height="match_parent"
                    android:layout_toRightOf="@+id/rel_textmoji"
                    android:layout_weight="1"
                    app:mrl_rippleColor="@color/mr_rippleColor"
                    app:mrl_rippleDelayClick="false"
                    app:mrl_rippleDuration="@integer/rippleDuration"
                    app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                    app:mrl_rippleHover="true"
                    app:mrl_rippleOverlay="true"
                    app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                    <RelativeLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent">

                        <ImageView
                            android:id="@+id/artmoji_view"
                            android:layout_width="wrap_content"
                            android:layout_height="match_parent"
                            android:layout_centerInParent="true"
                            android:src="@drawable/art_normal" />
                    </RelativeLayout>
                </com.balysv.materialripple.MaterialRippleLayout>


                <RelativeLayout
                    android:id="@+id/ic_delete_text_lay"
                    android:layout_width="50dp"
                    android:layout_height="match_parent"
                    android:layout_alignParentRight="true"
                    android:layout_weight="1"
                    android:visibility="invisible">

                    <ImageView
                        android:id="@+id/ic_delete_text"
                        android:layout_width="wrap_content"
                        android:layout_height="match_parent"
                        android:layout_centerInParent="true"
                        android:src="@drawable/ic_smiles_backspace_active" />
                </RelativeLayout>
            </RelativeLayout>
        </RelativeLayout>

        <RelativeLayout
            android:id="@+id/clipboard_layout"
            android:layout_width="match_parent"
            android:layout_height="191dp"
            android:background="@color/diy_art_box_color"
            android:visibility="gone">

            <RelativeLayout
                android:layout_width="match_parent"
                android:layout_height="match_parent">

                <RelativeLayout
                    android:id="@+id/clipboard_top"
                    android:layout_width="match_parent"
                    android:layout_height="40dp"
                    android:background="@color/diy_main_bg_color">

                    <com.balysv.materialripple.MaterialRippleLayout
                        android:id="@+id/clipboard_backword_layout"
                        android:layout_width="50dp"
                        android:layout_height="match_parent"
                        android:layout_weight="1"
                        app:mrl_rippleColor="@color/mr_rippleColor"
                        app:mrl_rippleDelayClick="false"
                        app:mrl_rippleDuration="@integer/rippleDuration"
                        app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                        app:mrl_rippleHover="true"
                        app:mrl_rippleOverlay="true"
                        app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                        <RelativeLayout
                            android:layout_width="match_parent"
                            android:layout_height="match_parent">

                            <ImageView
                                android:id="@+id/clipboard_backword"
                                android:layout_width="wrap_content"
                                android:layout_height="match_parent"
                                android:layout_centerInParent="true"
                                android:layout_marginLeft="10dp"
                                android:src="@drawable/ic_backword" />
                        </RelativeLayout>
                    </com.balysv.materialripple.MaterialRippleLayout>

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_centerInParent="true"
                        android:text="CLIP BOARD "
                        android:textColor="@color/white"
                        android:textSize="16dp" />

                    <com.balysv.materialripple.MaterialRippleLayout
                        android:id="@+id/lay_clipboard_keyboardword"
                        android:layout_width="50dp"
                        android:layout_height="match_parent"
                        android:layout_alignParentRight="true"
                        android:layout_weight="1"
                        app:mrl_rippleColor="@color/mr_rippleColor"
                        app:mrl_rippleDelayClick="false"
                        app:mrl_rippleDuration="@integer/rippleDuration"
                        app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                        app:mrl_rippleHover="true"
                        app:mrl_rippleOverlay="true"
                        app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                        <RelativeLayout
                            android:layout_width="match_parent"
                            android:layout_height="match_parent">

                            <ImageView
                                android:id="@+id/clipboard_keyboardword"
                                android:layout_width="wrap_content"
                                android:layout_height="match_parent"
                                android:layout_centerInParent="true"
                                android:layout_marginRight="10dp"
                                android:src="@drawable/ic_keyboardword" />
                        </RelativeLayout>
                    </com.balysv.materialripple.MaterialRippleLayout>
                </RelativeLayout>

                <LinearLayout
                    android:id="@+id/clipboard_list"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_below="@+id/clipboard_top"
                    android:background="#0000"
                    android:orientation="vertical"
                    android:visibility="gone">

                    <ImageView
                        android:id="@+id/list_clipboard"
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:layout_gravity="center"
                        android:src="@drawable/clipboard" />

                    <ListView
                        android:id="@+id/cliplist"
                        android:layout_width="match_parent"
                        android:layout_height="wrap_content"
                        android:visibility="visible"></ListView>

                    <TextView
                        android:id="@+id/emptyElement"
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:layout_centerInParent="true"
                        android:layout_gravity="center"
                        android:layout_marginTop="80dp"
                        android:gravity="center"
                        android:text="Your Clipborad is empty"
                        android:textColor="@color/white"
                        android:textSize="15sp"
                        android:visibility="gone" />
                </LinearLayout>

                <LinearLayout
                    android:id="@+id/clipboard_bottom"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_below="@+id/clipboard_top"
                    android:background="@color/diy_art_box_color"
                    android:orientation="vertical"
                    android:visibility="visible"
                    android:weightSum="2">

                    <LinearLayout
                        android:layout_width="match_parent"
                        android:layout_height="match_parent"
                        android:orientation="vertical"
                        android:weightSum="2">

                        <LinearLayout
                            android:layout_width="match_parent"
                            android:layout_height="match_parent"
                            android:layout_weight="0.3">

                            <LinearLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_marginLeft="20dp"
                                android:layout_weight="1.2">

                                <LinearLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:orientation="vertical"
                                    android:weightSum="2">

                                    <RelativeLayout
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:layout_weight="1">

                                        <ImageView
                                            android:id="@+id/ic_selectAll"
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_centerInParent="true"
                                            android:src="@drawable/select_all" />

                                        <ImageView
                                            android:id="@+id/ic_cut"
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_centerInParent="true"
                                            android:src="@drawable/ic_cut"
                                            android:visibility="gone" />
                                    </RelativeLayout>

                                    <RelativeLayout
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:layout_weight="1">

                                        <ImageView
                                            android:id="@+id/simple_copy"
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_centerInParent="true"
                                            android:src="@drawable/simple_copy" />
                                    </RelativeLayout>
                                </LinearLayout>
                            </LinearLayout>

                            <RelativeLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_weight="0.6">

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent">

                                    <ImageView
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_centerInParent="true"
                                        android:src="@drawable/ic_circle" />
                                </RelativeLayout>

                                <RelativeLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent">

                                    <ImageView
                                        android:id="@+id/ic_select"
                                        android:layout_width="@dimen/_40sdp"
                                        android:layout_height="@dimen/_37sdp"
                                        android:layout_centerInParent="true"
                                        android:src="@drawable/ic_unselects" />

                                    <RelativeLayout
                                        android:id="@+id/ic_arrowdown"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_below="@+id/ic_select"
                                        android:layout_centerHorizontal="true"
                                        android:paddingLeft="15dp"
                                        android:paddingTop="18dp"
                                        android:paddingRight="15dp"
                                        android:paddingBottom="10dp">

                                        <ImageView
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:src="@drawable/ic_arrowdown" />
                                    </RelativeLayout>

                                    <RelativeLayout
                                        android:id="@+id/ic_arrowup"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_above="@+id/ic_select"
                                        android:layout_centerHorizontal="true"
                                        android:paddingLeft="15dp"
                                        android:paddingTop="10dp"
                                        android:paddingRight="15dp"
                                        android:paddingBottom="18dp">

                                        <ImageView
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:src="@drawable/ic_arrowup" />
                                    </RelativeLayout>

                                    <RelativeLayout
                                        android:id="@+id/ic_arrowright"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_centerVertical="true"
                                        android:layout_toRightOf="@+id/ic_select"
                                        android:paddingLeft="18dp"
                                        android:paddingTop="15dp"
                                        android:paddingRight="10dp"
                                        android:paddingBottom="15dp">

                                        <ImageView
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:src="@drawable/ic_arrowright" />
                                    </RelativeLayout>

                                    <RelativeLayout
                                        android:id="@+id/ic_arrowleft"
                                        android:layout_width="wrap_content"
                                        android:layout_height="wrap_content"
                                        android:layout_centerVertical="true"
                                        android:layout_toLeftOf="@+id/ic_select"
                                        android:paddingLeft="10dp"
                                        android:paddingTop="15dp"
                                        android:paddingRight="18dp"
                                        android:paddingBottom="15dp">

                                        <ImageView
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:src="@drawable/ic_arrowleft" />
                                    </RelativeLayout>
                                </RelativeLayout>
                            </RelativeLayout>

                            <LinearLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent"
                                android:layout_marginRight="20dp"
                                android:layout_weight="1.2">

                                <LinearLayout
                                    android:layout_width="match_parent"
                                    android:layout_height="match_parent"
                                    android:orientation="vertical"
                                    android:weightSum="2">

                                    <RelativeLayout
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:layout_weight="1">

                                        <ImageView
                                            android:id="@+id/ic_paste"
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_centerInParent="true"
                                            android:src="@drawable/ic_paste" />
                                    </RelativeLayout>

                                    <RelativeLayout
                                        android:layout_width="match_parent"
                                        android:layout_height="match_parent"
                                        android:layout_weight="1">

                                        <ImageView
                                            android:id="@+id/ic_delete"
                                            android:layout_width="wrap_content"
                                            android:layout_height="wrap_content"
                                            android:layout_centerInParent="true"
                                            android:src="@drawable/ic_delete" />
                                    </RelativeLayout>
                                </LinearLayout>
                            </LinearLayout>
                        </LinearLayout>

                        <LinearLayout
                            android:layout_width="match_parent"
                            android:layout_height="match_parent"
                            android:layout_weight="1.7">

                            <RelativeLayout
                                android:layout_width="match_parent"
                                android:layout_height="match_parent">

                                <ImageView
                                    android:id="@+id/ic_clipboard"
                                    android:layout_width="wrap_content"
                                    android:layout_height="wrap_content"
                                    android:layout_alignParentBottom="true"
                                    android:layout_centerHorizontal="true"
                                    android:src="@drawable/clipboard" />
                            </RelativeLayout>
                        </LinearLayout>
                    </LinearLayout>
                </LinearLayout>
            </RelativeLayout>
        </RelativeLayout>

        <RelativeLayout
            android:id="@+id/netwrok_layout"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_centerInParent="true"
            android:background="@color/diy_main_bg_color"
            android:visibility="gone">

            <RelativeLayout
                android:id="@+id/root_layout21"
                android:layout_width="match_parent"
                android:layout_height="wrap_content">

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:gravity="center"
                    android:orientation="vertical">

                    <ImageView
                        android:layout_width="40dp"
                        android:layout_height="40dp"
                        android:layout_marginTop="55dp"
                        android:src="@drawable/ic_no_wifi" />

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_marginTop="5dp"
                        android:text="@string/network_error"
                        android:textColor="@color/white"
                        android:textSize="16dp"
                        android:textStyle="bold" />

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_marginLeft="10dp"
                        android:layout_marginTop="6dp"
                        android:layout_marginRight="10dp"
                        android:gravity="center"
                        android:text="@string/network_try_again"
                        android:textColor="@color/white"
                        android:textSize="16dp" />

                    <com.balysv.materialripple.MaterialRippleLayout
                        android:id="@+id/refresh_layout_click"
                        android:layout_width="wrap_content"
                        android:layout_height="38dp"
                        android:layout_centerVertical="true"
                        android:layout_marginTop="15dp"
                        android:layout_marginBottom="10dp"
                        app:mrl_rippleColor="@color/mr_rippleColor"
                        app:mrl_rippleDuration="@integer/rippleDuration"
                        app:mrl_rippleFadeDuration="@integer/rippleFadeDuration"
                        app:mrl_rippleRoundedCorners="@dimen/rippleRoundedCorners">

                        <RelativeLayout
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:background="@drawable/outline_layout_selector"
                            android:gravity="center">

                            <TextView
                                android:layout_width="wrap_content"
                                android:layout_height="wrap_content"
                                android:layout_centerInParent="true"
                                android:fontFamily="sans-serif-light"
                                android:paddingLeft="50dp"
                                android:paddingRight="50dp"
                                android:text="@string/network_refresh"
                                android:textColor="@color/white"
                                android:textSize="16dp" />
                        </RelativeLayout>
                    </com.balysv.materialripple.MaterialRippleLayout>
                </LinearLayout>

                <RelativeLayout
                    android:id="@+id/close_layout"
                    android:layout_width="match_parent"
                    android:layout_height="40dp"
                    android:background="@color/diy_art_box_color"
                    android:visibility="visible">

                    <ImageView
                        android:id="@+id/nonetwork_back"
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_centerVertical="true"
                        android:layout_marginLeft="10dp"
                        android:src="@drawable/ic_backword" />

                    <ImageView
                        android:id="@+id/net_closedialog"
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_alignParentRight="true"
                        android:layout_centerVertical="true"
                        android:layout_marginRight="10dp"
                        android:src="@drawable/ic_keyboardword" />
                </RelativeLayout>

            </RelativeLayout>
        </RelativeLayout>


        <RelativeLayout
            android:id="@+id/lang"
            android:layout_width="wrap_content"
            android:layout_height="fill_parent"
            android:hardwareAccelerated="false"
            android:visibility="gone">

            <androidx.cardview.widget.CardView
                android:layout_width="fill_parent"
                android:layout_height="wrap_content"
                android:hardwareAccelerated="false"
                app:cardBackgroundColor="@android:color/transparent">


                <LinearLayout
                    android:layout_width="fill_parent"
                    android:layout_height="fill_parent"
                    android:layout_gravity="center"
                    android:orientation="vertical">

                    <LinearLayout
                        android:layout_width="match_parent"
                        android:layout_height="25dp"
                        android:layout_marginRight="6dp"
                        android:background="@color/white"
                        android:gravity="right">

                        <ImageView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_alignParentRight="true"
                            android:layout_gravity="right"
                            android:layout_marginRight="5dp"
                            android:scaleType="centerInside"
                            android:src="@drawable/ic_roundshape_close" />
                    </LinearLayout>

                    <ListView
                        android:layout_width="fill_parent"
                        android:layout_height="fill_parent"
                        android:background="@color/white"
                        android:visibility="visible" />
                </LinearLayout>
            </androidx.cardview.widget.CardView>
        </RelativeLayout>

    </RelativeLayout>
</RelativeLayout>
